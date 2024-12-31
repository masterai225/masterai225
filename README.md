- 👋 Hi, I’m @masterai225
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
masterai225/masterai225 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->import openai

openai.api_key = "YOUR_API_KEY"

response = openai.Image.create(
    prompt="A futuristic cityscape",
    n=1,
    size="1024x1024"
)

print(response['data'][0]['url'])
