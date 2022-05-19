[![Typing SVG](https://readme-typing-svg.herokuapp.com?color=4691E4&lines=Hello+world!%2C+I'm+N0tFake)](https://git.io/typing-svg)

```c
#include <stdio.h>
#include <string.h>

typedef struct {
  char name[50];
  char country[50];
  int isStudent;
} MyProfile;

int main(){

  MyProfile Profile;

  strcpy(Profile.name, "Silvio Otávio");
  strcpy(Profile.country, "Brazil");
  Profile.isStudent = 1;
  
  printf("My name is %s\n", Profile.name);
  printf("I am from  %s\n", Profile.country);
  
  if(Profile.isStudent == 1){
    printf("I am a computer science student\n");
  }
  
  return 0;
}
```


![Snake animation](https://github.com/N0tFake/N0tFake/blob/output/github-contribution-grid-snake.svg)
<!--
**N0tFake/N0tFake** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
