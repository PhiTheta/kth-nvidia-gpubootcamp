CXX=mpic++
CXXFLAGS=-fast -Minfo=all -ta=tesla:managed
LDFLAGS=-lpnetcdf

main: miniWeather_mpi.o
	$(CXX) $(CXXFLAGS) -o $@ $^ $(LDFLAGS)

.PHONY: clean
clean:
	rm -f *.o *main core
.SUFFIXES:
.SUFFIXES: .cpp .o 
.cpp.o:
	$(CXX) -c -o $@ $(CXXFLAGS) $<
