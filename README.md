first 
Download the environment variables needed to connect Next.js and Studio to your Sanity project:

npx vercel env pull

second

Needed for live previewing unpublished/draft content.




npm install 

and last 

npm run dev

in other terminal
for sanity studio 

npm run studio:dev

remember .env with the project id and stuff

thats it

enjoy

/*-env": "npx @sanity/cli install && copy ../.env .env.development || copy ../.env.local .env.development"*/

NEXT_PUBLIC_SANITY_PROJECT_ID=jpt74xrj
NEXT_PUBLIC_SANITY_DATASET=production
SANITY_API_READ_TOKEN=skh4LJiAXxv6xkyUdN5fu1zev52aiZo0xcE3g9JgbRT9yqWaNezhxoQIsIsh1rEfNRoJ7pzp924P5grHCf3wrySOUw4hFKjcjwggxgdggrr7EMyZIiZIsQZ8QWn3ogcfmLhmMQeOxcHzUm5Zjn2LrzVyMO703b6y0U0Wm8M3hCcqSO4AS7ij
SANITY_REVALIDATE_SECRET=

ya sirviendo el build
