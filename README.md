# Workshop: AI Fairytale

![NOA](https://www.sympa.com/hubfs/Noa%20logo%20grey.png)

Read more @
https://noa-ai-workshop.vercel.app/

Template by:
- [Github](https://github.com/thenorthalliance/AI-Workshop)

Project powered by:
- Next.js
- Sanity
- OpenAI

---

## Steps to run the code

1. Create a Sanity account and a Sanity project to get the `projectId`.

2. Create an OpenAI account to get the `openai api key`.

3. Add .env file in the root directory containing:
- NEXT_PUBLIC_SANITY_PROJECT_ID="ENTER SANITY PROJECT ID HERE"
- NEXT_PUBLIC_SANITY_DATASET="production"
- NEXT_PUBLIC_SANITY_PROJECT_TITLE="AI-Workshop"
- NEXT_PUBLIC_SANITY_API_VERSION="2022-11-15"
- NEXT_PUBLIC_OPENAI_API_KEY="ENTER OPENAI API KEY HERE"
- NEXT_PUBLIC_CHEAT_CODE_1=""
- NEXT_PUBLIC_CHEAT_CODE_2=""
- NEXT_PUBLIC_CHEAT_CODE_3=""

4. Run `npm install` in terminal while in the root directory.

5. Use `npm run dev` to start the development server.

6. Navigate to your Sanity studio management page and select your project, navigate to the API tab and add `http://localhost:3000/studio` to the CORS Origins list.

7. Open your web browser at `http://localhost:3000/studio`.