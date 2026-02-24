# UnitigPro
A command line tool that processes large unitig files from unitig-caller and transforms them into: 
1. A sparse matrix allowing sensible manipulation of the data
2. Transposes the matrix such that the unitig sequences are columns and Isolate IDs are rows
3. Drops unitigs that are invariant across the set of isolates (present or absent in all)
5. Saves the sparse matrix as a npz file
6. 
