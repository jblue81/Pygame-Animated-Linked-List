# Pygame-Animated-Linked-List

`"Animated Linked List"` - This project presents an example of an animated linked list created using the Pygame library. Each node is represented as a circle, and the connections between the nodes are shown with colored lines. Additionally, this animation moves the node list according to the mouse position and offers customization options for the growth rate, position, and connections of the nodes.

## Requirements
+ `Python 3`
+ `Pygame`

## Installation
1. Install `Python 3` on your computer.
2. Download or clone the project to your computer.
3. Open the terminal or command prompt and navigate to the project directory.
4. Run the `pip install -r requirements.txt` command to install the required libraries.
5. Launch the program by running the `main.py` file.

## Usage
> This project uses the LinkedList class to provide visual representation of the linked list. The AnimatedList class extends the LinkedList class to make the linked list animated. Additionally, it is possible to customize the appearance of the linked list by adjusting growth rate and position modification functions.

## File Description:
| Value | Description |
| ------ | ----------- |
| main.py | This file is the main file where the process of creating the animated graphic takes place. |
| constants.py | This file is a file where constants are defined. These constants include various values used in the process of creating the graphic. |
| linked_list.py | This file is a file where the linked list data structure is defined. This data structure is used in the process of creating the graphic. |
| animated_list.py | This file is a file where the class for creating an animated graphic using the linked list data structure is defined. |

## Customization:

The following options are available to change the connections and positions of the nodes:
| Value | Description |
| ------ | ----------- |
| growth_rate_function | Takes a function to determine the growth rate of the nodes. By default, the `x/30` function is used. |
| pos_modifier_function | Takes a function to determine the position of the nodes. By default, the `math.cos(z*2)50` and `math.sin(z2)*50` functions are used. |
| draw_links | Determines whether the connections should be drawn or not. By default, it is set to `True`. |
| draw_nodes | Determines whether the nodes should be drawn or not. By default, it is set to `True`. |

## Lists Customization Details
__`To customize this project, you can follow these steps:`__

+ Change the constants in the __constants.py__ file. For example, you can change the growth rate of the nodes `GROWTH_RATE` or change the `NODE_FILL` constant to draw nodes instead of filling them.
+ Customize the growth rate, position, and connections of the nodes by modifying the init function of the AnimatedList class. For example, you can change the `growth_rate_function` and `pos_modifier_function` functions to adjust the position and growth rate of the nodes.
+ Customize the movement of the nodes by modifying the `animation_update` function of the AnimatedList class. This function allows the connections of the nodes to be drawn and their positions to be updated.

### Contributing
If you want to contribute to the project, please open an issue or a pull request on the project's GitHub repository.
