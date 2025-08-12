[vercel.json](https://github.com/user-attachments/files/21740729/vercel.json)
{
  "functions": { "api/*.js": { "runtime": "nodejs18.x" } },
  "routes": [
    { "src": "/api/(.*)", "dest": "/api/$1.js" }
  ]
}
