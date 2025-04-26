```python
def RecursiveMario(img, size):
    plot(img, size)
    RecursiveMario(img, size - 10)
```


<p align="left">
  <img class="gatsby-resp-image-image" src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/dee38e10-db68-462d-9df7-46b87d4c7876/ddxh2po-85a87439-ac1f-49d7-a828-6b78d768b403.gif?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7InBhdGgiOiJcL2ZcL2RlZTM4ZTEwLWRiNjgtNDYyZC05ZGY3LTQ2Yjg3ZDRjNzg3NlwvZGR4aDJwby04NWE4NzQzOS1hYzFmLTQ5ZDctYTgyOC02Yjc4ZDc2OGI0MDMuZ2lmIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmZpbGUuZG93bmxvYWQiXX0.TGsrcvN8-1L5EmrOSnRRtcffJfUkkdFtLzztr_mjy5Q" width="95">
    <img class="gatsby-resp-image-image" src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/dee38e10-db68-462d-9df7-46b87d4c7876/ddxh2po-85a87439-ac1f-49d7-a828-6b78d768b403.gif?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7InBhdGgiOiJcL2ZcL2RlZTM4ZTEwLWRiNjgtNDYyZC05ZGY3LTQ2Yjg3ZDRjNzg3NlwvZGR4aDJwby04NWE4NzQzOS1hYzFmLTQ5ZDctYTgyOC02Yjc4ZDc2OGI0MDMuZ2lmIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmZpbGUuZG93bmxvYWQiXX0.TGsrcvN8-1L5EmrOSnRRtcffJfUkkdFtLzztr_mjy5Q" width="85">
    <img class="gatsby-resp-image-image" src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/dee38e10-db68-462d-9df7-46b87d4c7876/ddxh2po-85a87439-ac1f-49d7-a828-6b78d768b403.gif?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7InBhdGgiOiJcL2ZcL2RlZTM4ZTEwLWRiNjgtNDYyZC05ZGY3LTQ2Yjg3ZDRjNzg3NlwvZGR4aDJwby04NWE4NzQzOS1hYzFmLTQ5ZDctYTgyOC02Yjc4ZDc2OGI0MDMuZ2lmIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmZpbGUuZG93bmxvYWQiXX0.TGsrcvN8-1L5EmrOSnRRtcffJfUkkdFtLzztr_mjy5Q" width="75">
    <img class="gatsby-resp-image-image" src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/dee38e10-db68-462d-9df7-46b87d4c7876/ddxh2po-85a87439-ac1f-49d7-a828-6b78d768b403.gif?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7InBhdGgiOiJcL2ZcL2RlZTM4ZTEwLWRiNjgtNDYyZC05ZGY3LTQ2Yjg3ZDRjNzg3NlwvZGR4aDJwby04NWE4NzQzOS1hYzFmLTQ5ZDctYTgyOC02Yjc4ZDc2OGI0MDMuZ2lmIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmZpbGUuZG93bmxvYWQiXX0.TGsrcvN8-1L5EmrOSnRRtcffJfUkkdFtLzztr_mjy5Q" width="65">
    <img class="gatsby-resp-image-image" src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/dee38e10-db68-462d-9df7-46b87d4c7876/ddxh2po-85a87439-ac1f-49d7-a828-6b78d768b403.gif?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7InBhdGgiOiJcL2ZcL2RlZTM4ZTEwLWRiNjgtNDYyZC05ZGY3LTQ2Yjg3ZDRjNzg3NlwvZGR4aDJwby04NWE4NzQzOS1hYzFmLTQ5ZDctYTgyOC02Yjc4ZDc2OGI0MDMuZ2lmIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmZpbGUuZG93bmxvYWQiXX0.TGsrcvN8-1L5EmrOSnRRtcffJfUkkdFtLzztr_mjy5Q" width="55">
    <img class="gatsby-resp-image-image" src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/dee38e10-db68-462d-9df7-46b87d4c7876/ddxh2po-85a87439-ac1f-49d7-a828-6b78d768b403.gif?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7InBhdGgiOiJcL2ZcL2RlZTM4ZTEwLWRiNjgtNDYyZC05ZGY3LTQ2Yjg3ZDRjNzg3NlwvZGR4aDJwby04NWE4NzQzOS1hYzFmLTQ5ZDctYTgyOC02Yjc4ZDc2OGI0MDMuZ2lmIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmZpbGUuZG93bmxvYWQiXX0.TGsrcvN8-1L5EmrOSnRRtcffJfUkkdFtLzztr_mjy5Q" width="45">
    <img class="gatsby-resp-image-image" src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/dee38e10-db68-462d-9df7-46b87d4c7876/ddxh2po-85a87439-ac1f-49d7-a828-6b78d768b403.gif?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7InBhdGgiOiJcL2ZcL2RlZTM4ZTEwLWRiNjgtNDYyZC05ZGY3LTQ2Yjg3ZDRjNzg3NlwvZGR4aDJwby04NWE4NzQzOS1hYzFmLTQ5ZDctYTgyOC02Yjc4ZDc2OGI0MDMuZ2lmIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmZpbGUuZG93bmxvYWQiXX0.TGsrcvN8-1L5EmrOSnRRtcffJfUkkdFtLzztr_mjy5Q" width="35">
</p>
    <img class="gatsby-resp-image-image" src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/dee38e10-db68-462d-9df7-46b87d4c7876/ddxh2po-85a87439-ac1f-49d7-a828-6b78d768b403.gif?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7InBhdGgiOiJcL2ZcL2RlZTM4ZTEwLWRiNjgtNDYyZC05ZGY3LTQ2Yjg3ZDRjNzg3NlwvZGR4aDJwby04NWE4NzQzOS1hYzFmLTQ5ZDctYTgyOC02Yjc4ZDc2OGI0MDMuZ2lmIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmZpbGUuZG93bmxvYWQiXX0.TGsrcvN8-1L5EmrOSnRRtcffJfUkkdFtLzztr_mjy5Q" width="25">
</p>
    <img class="gatsby-resp-image-image" src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/dee38e10-db68-462d-9df7-46b87d4c7876/ddxh2po-85a87439-ac1f-49d7-a828-6b78d768b403.gif?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7InBhdGgiOiJcL2ZcL2RlZTM4ZTEwLWRiNjgtNDYyZC05ZGY3LTQ2Yjg3ZDRjNzg3NlwvZGR4aDJwby04NWE4NzQzOS1hYzFmLTQ5ZDctYTgyOC02Yjc4ZDc2OGI0MDMuZ2lmIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmZpbGUuZG93bmxvYWQiXX0.TGsrcvN8-1L5EmrOSnRRtcffJfUkkdFtLzztr_mjy5Q" width="15">
</p>
<img class="gatsby-resp-image-image" src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/dee38e10-db68-462d-9df7-46b87d4c7876/ddxh2po-85a87439-ac1f-49d7-a828-6b78d768b403.gif?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7InBhdGgiOiJcL2ZcL2RlZTM4ZTEwLWRiNjgtNDYyZC05ZGY3LTQ2Yjg3ZDRjNzg3NlwvZGR4aDJwby04NWE4NzQzOS1hYzFmLTQ5ZDctYTgyOC02Yjc4ZDc2OGI0MDMuZ2lmIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmZpbGUuZG93bmxvYWQiXX0.TGsrcvN8-1L5EmrOSnRRtcffJfUkkdFtLzztr_mjy5Q" width="5">
</p>

<div>
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=bruniculos08&show_icons=true&theme=nord"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=bruniculos08&layout=compact&langs_count=16&theme=nord"/>
</div>

## Welcome, I'm Bruno Rafael dos Santos!

[![Linkedin](https://img.shields.io/badge/Linkedin-7078F8?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bruno-rafael-dos-santos-6743031b7/)



<!--
[![Other links](https://img.shields.io/badge/other_links-006d6b?style=for-the-badge&logo=cs&logoColor=green)]()

- [My Link's note](https://github.com/bruniculos08/Outros/blob/93eb928f7ea6a743455dd180608e449901f9765e/Lista%20de%20Links.md) 

- [My Twitter](https://twitter.com/bruno_rafasan)

- [My Instagram](https://www.instagram.com/bruno_rafasan/)

- [My Curriculum](https://github.com/bruniculos08/Outros/blob/ea2d565aa93afec9764f2770cdd326f3e6513295/CS_IT_SWE_Resume_Template.pdf
)




   <img height="180em" src="https://github-readme-stats.vercel.app/api/wakatime?username=bruniculos08"/>

[![willianrod's wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=bruniculos08)](https://github.com/anuraghazra/github-readme-stats)

<p align="left">
  <img class="gatsby-resp-image-image" src="https://1b-f.s3.eu-west-1.amazonaws.com/a/175146-E22F2BDB-F534-45FC-A6F8-E1AB5233844D-0-1619119410.gif" height="300" width="900">
</p>

<p align="center">
  <img class="gatsby-resp-image-image" src="https://i.pinimg.com/originals/cf/e9/3a/cfe93a55232f27627a66a2a367fe1c4c.gif" width="100">
</p>

<p align="center">
  <img class="gatsby-resp-image-image" src="https://static.wixstatic.com/media/5c1b3e_6bda1190a9c44afcafdb1d2b9072ac77~mv2.gif" width="200">
  <img class="gatsby-resp-image-image" src="https://thumbs.gfycat.com/OldEuphoricKarakul-max-1mb.gif" width="200">
</p>

<p align="center">
  <img class="gatsby-resp-image-image" src="https://static.wixstatic.com/media/39d8e3_b78cf95bad104bca97b127ac97e58735~mv2.gif/v1/fit/w_281,h_281,q_90/39d8e3_b78cf95bad104bca97b127ac97e58735~mv2.gif" width="300">
</p>

<p align="left">
  <img class="gatsby-resp-image-image" src="https://64.media.tumblr.com/cca4f06484b447c0687f0325af5b38c9/428a8db1dc8ae92f-87/s1280x1920/7c751558b1d93e15c2d885cff2162ddb95059b8d.gifv" width="750">
</p>


<!--
## **Hi there, i am Bruno Rafael dos Santos.** 

#### Readme:
- [Artigo de exemplos](https://raullesteves.medium.com/github-como-fazer-um-readme-md-bonit%C3%A3o-c85c8f154f8) 

#### Twitter:

- [@bruno_rafasan](https://twitter.com/bruno_rafasan) 


<!--
**bruniculos08/bruniculos08** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...👋
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->


