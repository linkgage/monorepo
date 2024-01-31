# monorepo

<img width="1020" alt="image" src="https://github.com/linkgage/monorepo/assets/42182955/b7898878-bc12-4fab-b386-96350fa54b3d">



#### powerhouse-of-linkgage

## Overview

This project aims to enhance the Knowledge Graph Platform by implementing a feature-rich Graph Editor. The editor will allow users to interactively create, manage, and visualize complex knowledge graphs with ease.

## Project Structure

The project structure is organized as follows:

- **src/components:** Contains React components for the Graph Editor, Nodes, and Edges.
- **src/utils:** Houses utility functions for graph manipulation.
- **public:** Includes the HTML entry point for the application.

```
knowledge-graph-editor/
|-- .github/
|   |-- workflows/
|       |-- build.yml
|-- public/
|   |-- index.html
|-- src/
|   |-- components/
|   |   |-- GraphEditor/
|   |       |-- GraphEditor.jsx
|   |       |-- Node/
|   |           |-- Node.jsx
|   |       |-- Edge/
|   |           |-- Edge.jsx
|   |-- utils/
|   |   |-- graphUtils.js
|-- tests/
|   |-- unit/
|       |-- GraphEditor.test.js
|-- .gitignore
|-- package.json
|-- README.md
|-- LICENSE
|-- .eslintrc.js
|-- .prettierrc

```
## Features

- **Node and Edge Manipulation:** Drag-and-drop interface for adding, moving, and connecting nodes.
- **Advanced Graph Operations:** Merge nodes, split edges, and handle multi-edge connections.
- **Visual Styling:** Customize node and edge visual representations.
- **Undo/Redo Functionality:** Robust history tracking for undoing and redoing actions.
- **Collaborative Editing:** Real-time collaboration for multiple users.
- **Import/Export:** Import and export graphs in common formats (RDF, JSON).

## Contributing

1. Fork the repository.
2. Create a new branch for your feature or bug fix: `git checkout -b feature-name`.
3. Make changes and commit: `git commit -m "Add feature-name"`.
4. Push to the branch: `git push origin feature-name`.
5. Submit a pull request.

## License

This project is licensed under the [Apache License 2.0](LICENSE).

## Contact

For any questions or feedback, feel free to contact us at ideas@linkgage.co.

Happy coding!
