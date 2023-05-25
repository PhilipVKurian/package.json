# package.json

{
  "name": "client",
  "version": "0.1.0",
  "private": true,
  "proxy": "http://localhost:3001",
  "dependencies": {
    "@apollo/client": "^3.7.10",
    "@apollo/react-hooks": "^4.0.0",
    "@emotion/react": "^11.10.6",
    "@emotion/styled": "^11.10.6",
    "@fortawesome/free-solid-svg-icons": "^6.3.0",
    "@fortawesome/react-fontawesome": "0.2.0",
    "@material-ui/core": "^4.12.3",
    "@material-ui/icons": "^4.11.2",
    "@material-ui/lab": "^4.0.0-alpha.60",
    "@mui/icons-material": "^5.11.11",
    "@mui/joy": "5.0.0-alpha.72",
    "@mui/material": "^5.11.14",
    "@react-pdf/renderer": "^3.1.9",
    "@stripe/react-stripe-js": "^2.1.0",
    "@stripe/stripe-js": "^1.52.0",
    "@testing-library/jest-dom": "^5.16.4",
    "@testing-library/react": "^11.1.0",
    "@testing-library/user-event": "^13.5.0",
    "bootstrap": "^5.2.3",
    "graphql": "^16.6.0",
    "graphql-tag": "^2.12.6",
    "jwt-decode": "^2.2.0",
    "react": "17.0.2",
    "react-bootstrap": "^2.7.2",
    "react-dom": "17.0.2",
    "react-router-dom": "^5.1.2",
    "react-scripts": "^5.0.1"
  },
  "devDependencies": {
    "@emotion/react": "^11.5.0",
    "@emotion/styled": "^11.3.0",
    "@types/react": "^17.0.0",
    "concurrently": "^5.1.0",
    "react-dom": "^17.0.0"
  },
  "scripts": {
    "start": "react-scripts start",
    "build": "react-scripts build",
    "test": "react-scripts test",
    "eject": "react-scripts eject"
  },
  "eslintConfig": {
    "extends": "react-app"
  },
  "browserslist": {
    "production": [
      ">0.2%",
      "not dead",
      "not op_mini all"
    ],
    "development": [
      "last 1 chrome version",
      "last 1 firefox version",
      "last 1 safari version"
    ]
  }
}
