# Unity Support Colombia: Memory Profiler Extension
Extension for the existing Unity memory profiler project, this is a WIP project made by the Unity Support Team in Colombia, which uses as a base the Memory Profiler project found in https://bitbucket.org/Unity-Technologies/memoryprofiler and uses the new memory profiler API introduced in Unity5.3a4, adding filters and search options with a node viewer for the objects and their references.

* Requires Unity 5.6 or newer in order to use the filters and table views
* For checking the Heap Memory Information and also for export objects list data (ordered by size) to an external .txt file you could use any version of Unity that supports the API: (e.g 5.3,5.4,5.5,5.6,2017) 
* Requires a IL2CPP build
* It uses the same snapshots taken with the Memory Profiler project from bitbucket (You can use as an example memory snapshot which is included in the repository)
* It's recommended to read snapshots taken from the same Unity version (for example analyse 5.6 snapshots using 5.6 editor,etc) 

![Alt text](/Documentation/Images/TreeView.jpg?raw=true "Memory Profiler Tree/Node Window")
![Alt text](/Documentation/Images/HeapView.jpg?raw=true "Memory Profiler Heap Window")
![Alt text](/Documentation/Images/PlainData.jpg?raw=true "Memory Profiler Plain Data Window")

