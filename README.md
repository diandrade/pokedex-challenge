# Jetpack Compose Pokedex

<img src="https://github.com/diandrade/Pokedex-Challenge/blob/cb67ea904f42e682957728ea821722d6d30ce1b1/img/WhatsApp%20Image%202022-08-22%20at%2007.45.05.jpeg" alt="JetNews" width="240"></img>
<img src="https://github.com/diandrade/Pokedex-Challenge/blob/784d3a24e31c9cf02ec833fdd67f7cb1f77ecc97/img/WhatsApp%20Image%202022-08-22%20at%2007.45.05%20(2).jpeg" alt="JetNews" width="240"></img>
<img src="https://github.com/diandrade/Pokedex-Challenge/blob/885ad43aa317ab55679afd46ac0d501964b99fee/img/WhatsApp%20Image%202022-08-22%20at%2007.45.05%20(1).jpeg" alt="JetNews" width="240"></img>
<img src="https://github.com/diandrade/Pokedex-Challenge/blob/cb67ea904f42e682957728ea821722d6d30ce1b1/img/WhatsApp%20Image%202022-08-22%20at%2007.45.06.jpeg" alt="JetNews" width="240"></img>

Hello! This is the Pokedex project I created for a challenge following the steps of YouTuber Philipp Lackner.

The challenge consists of creating two lists: one with Pokémon fetched from the Pokémon API, found [HERE](insert-link), displaying available Pokémon, where you need to click to access the specific Pokémon’s details.

The other list shows saved Pokémon.

The mandatory information for each Pokémon includes:

● ID

● Name

● Type (grass, fire, water)

● Photo

Additionally, following Philipp's steps, we also added the weight, height, and stats of each Pokémon.

## Technical Specifications

Technologies/Design Patterns used in the Challenge:

● MVVM (Mandatory)

● Room (Mandatory)

● Ktor or Retrofit (Mandatory)

● Coroutine (Mandatory)

● Jetpack Compose (Optional)

● Dependency Injection (Optional)

## Challenges

Although I did a lot of research, several changes in app development technologies occurred since Philipp’s videos. As a result, I often had to research these changes, such as those in the Coil framework. Also, there were changes in the base project version, as well as the current versions of Gradle, Kotlin, and Hilt.

A notable challenge was creating the second list. Even after several attempts, I faced difficulties using Room with Jetpack Compose. I decided to focus on finishing the first list and adding the favorite feature as part of the next steps.

## Project Presentation

If you'd like to see the project in action, here are two videos available through YouTube’s unlisted option:

● **App Presentation on Mobile**

Since the mobile device didn’t capture the audio very well, I’ll detail the video here. In the video, we see the project starting up. After initialization, the first list appears, showing all Pokémon from the API, complete with profile pictures and predefined styling based on the base project available [here](insert-link).

After clicking on the chosen Pokémon, you get access to the Pokémon’s ID, name, type, profile photo, weight, height, and stats.

At the end of the first list, there’s an option to favorite or unfavorite the Pokémon at the top of the screen.

● **Coding Summary**

In this video, I explain some of the challenges faced during the project using Android Studio, as well as a general overview of the coding process.

I also discuss the lessons learned during the development of this project.










