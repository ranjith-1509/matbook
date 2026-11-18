# Workflow Builder (React + React Flow + Firebase)

A web app for creating, saving and viewing visual workflows as flowcharts.

## Features
- **Sign in** with Firebase Authentication; workflow pages are protected routes.
- **Workflow list:** see your saved workflows, with pin/unpin and status icons.
- **Flowchart editor:** build a workflow visually with React Flow (start and end nodes, connections), then save it with a name and description.
- **Viewer:** open a saved workflow as a read-only flowchart.

## Tech
React 18, React Router, React Flow, Firebase (Auth), Axios.

## Run locally
```bash
npm install
# add your Firebase web config as REACT_APP_FIREBASE_* variables in a .env file
npm start
```

## Project structure
```
src/
  pages/        Login, List, CreateFlowChart, FlowChart (viewer)
  components/   PrivateRoute, SaveWorkflowModal
  config/       Firebase setup
  data/         sample workflows
```
