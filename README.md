# The Future in Tech Podcast

<img src="https://raybo.org/tfit-feed/images/artwork.jpg" width="250">

**The Future in Tech** is a weekly podcast series powered by [LinkedIn Learning](https://www.linkedin.com/learning/) and hosted by Senior Staff Instructor [Ray Villalobos](https://www.linkedin.com/in/planetoftheweb).

The podcast aims to spark conversations, provide practical tips, and share resources to help developers work, learn, and tackle challenges in the technology industry.

We discuss topics like **Generative AI tools** (ChatGPT, DALL·E 2, Hugging Face) by talking to leaders building these tools. Episodes cover how professionals broke into technology, business strategies, ethical concerns, and the technical skills required for the future of work.

Guests include people who are building next-generation AI tools and leaders who have worked for or with **Fortune 500 companies** like Microsoft, Google, LinkedIn, IBM, OpenAI, and more.

---

## How to Listen

You can follow the podcast through various platforms:

- [Podcast Website](https://go.raybo.org/tfit)  
- [Episode Guide](https://go.raybo.org/tfit-episodes)  
- [YouTube Playlist](https://go.raybo.org/tfit-youtube)  
- [Podcast RSS Feed (Audio Only)](https://go.raybo.org/tfit-feed-audio)  
- [Episode Newsletter](https://go.raybo.org/tfit-newsletter)  

---

## About This Repository

This repository contains:

- `feed.yml` – The source YAML file for the podcast episodes.  
- `feed.py` – Python script that generates `podcast.xml` (RSS feed) from `feed.yml`.  
- `entrypoint.sh` – Shell script for GitHub Actions to automate feed generation and commit updates.  
- `.github/workflows/main.yml` – GitHub Action workflow for automated RSS feed updates.

**Automated Workflow:**

1. Update `feed.yml` with new episode information.  
2. GitHub Actions runs `feed.py` to generate `podcast.xml`.  
3. Changes are committed and pushed automatically.  
4. The RSS feed can be served via GitHub Pages for podcast distribution.

---

## Contribution

You can contribute by:

- Submitting pull requests to update `feed.yml`.  
- Improving `feed.py` or automation scripts.  
- Reporting issues related to RSS feed generation or formatting.

---

## License

This repository is licensed under the **MIT License**.
