first 
Download the environment variables needed to connect Next.js and Studio to your Sanity project:

npx vercel env pull

second

Needed for live previewing unpublished/draft content.

npm --prefix studio run cors:add -- http://localhost:3000 --credentials

npm install 

and last 

npm run dev

in other terminal
for sanity studio 

npm run studio:dev
