The Blueprint Visual Script Editor is used to create logic and behavior for our [[Blueprint Class|Blueprint Classes]].
The logic is defined by [[Execution Nodes]] that are linked together via their execution pins and [[Expression Nodes]] that control and configure the [[Execution Nodes]] for each execution, and [[Value Nodes]] that provide input to both the [[Execution Nodes]] and the [[Expression Nodes]].

# Creating nodes
New nodes are added to the Visual Script by right-clicking and then selecting the wanted node from the list that appears.
The node list can be filtered.

References to [[Blueprint Variables]] can be created either from the right-click menu or by dragging the variable into the graph from the Variables category int he My Blueprint panel.
Upon release we get to chose if we want a get node or a set node.
By holding CTRL while dragging we create a get node immediately.
By holding Alt while dragging we create a set node immediately.

# Connecting nodes
Nodes are connected at their input and output pins with wires.
An input pin can be connected to an output pin by dragging from one to the other.

# Organizing nodes and wires
Reroute nodes can be created by double-clicking on a wire.

# Zoom
We can zoom the graph in and out using the scroll wheel on the mouse.
By default the max zoom is 1:1.
By holding control we allow zooming in further than 1:1, giving us magnification.

# Comments
A collection of nodes can be surrounded by a comment.
This is a bit like a grouping in that moving the comment will move all the nodes inside it.
Comment can be colored and have different text sizes, both edited from the Details panel.