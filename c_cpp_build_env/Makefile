infile = main
out = exec.exe

default:
	g++ -O3 -v -Wpedantic -Wall -Wextra -Wwrite-strings --extra-warnings -g3 -o $(out) $(infile).cpp
#	gcc -O3 -v -Wpedantic -Wall -Wextra -Wwrite-strings --extra-warnings -g3 -o $(out) $(infile).c
	powershell -Command "Write-Host ''; .\$(out); Write-Host ''"