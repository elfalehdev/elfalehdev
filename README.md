# 01101000 01100101 01101100 01101100 01101111  👋

```Shell
from django.views.generic.detail import DetailView

class AboutMe(DetailView):
  name = "Mohamed E.Faleh"
  location = "Qabis, Tunisia"
  education = "Computer Science"
  website = "KMx404.github.io"
  
   #get social media links
  def get_social_contact(self):
    social_media_links = {
      "facebook": "facebook.com/KMx404"
      "instagram": "instagram.com/KMx404"
      "twitter": "twitter.com/KMx404"
      "dev community" : "dev.to/KMx404"      
    }    
    return social_media_links 
  
  #get all my favourite  programming languages
  def get_fav_lang(self):
      languages = ['python 🐍 ', 'javascript😺 ', 'C++❤️']
      return languages
      
  #get all my favourite frameworks
  def get_fav_frameworks(self):
    frameworks = ['django 🔫 ', 'react 🎯', 'bootstrap✨' ]
    return frameworks
   
  #get the databases that i can use
  def get_databases(self):
   data_bases = ['mysql 👍', 'mongodb 🍃']
   return data_bases
   ```
   
[![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=KMx404)](https://github.com/anuraghazra/github-readme-stats) [![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=KMx404&layout=compact)](https://github.com/anuraghazra/github-readme-stats)
