{
  "name": "My Python App",
  "description": "UI for Pagidi project",
  "scripts": {
    "start": "python app.py",
    "test": "pytest",
    "build": "echo 'No build step required for Python project'"
  },
  "keywords": ["UI", "Pagidi", "Heroku"],
  "repository": {
    "type": "git",
    "url": "https://git.heroku.com/pyf.git"
  },
  "env": {
    "NODE_ENV": "production",
    "API_URL": "https://api.pagidi-ui.com"
  },
"environments": {
    "test": {
      "formation": {
          "test": {
            "quantity": 1"
  "formation": {
    "web": {
" python"
      : "app:pyf",
      "quantity": 1,
      "size": "standard-1x"
    }
  },
  "addons": [],
  "buildpacks": [
    { "url": "rediss://:pc9879b60cba8b1eeb19b0c0625eebc5fb61352ca62a031539b9e4d5da0c90c3e@ec2-44-196-2-223.compute-1.amazonaws.com:28190
" }
  ]
}
