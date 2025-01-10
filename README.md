# Jetpack Compose Pokedex

![Pokémon 1](https://github.com/diandrade/Pokedex-Challenge/blob/cb67ea904f42e682957728ea821722d6d30ce1b1/img/WhatsApp%20Image%202022-08-22%20at%2007.45.05.jpeg)
![Pokémon 2](https://github.com/diandrade/Pokedex-Challenge/blob/784d3a24e31c9cf02ec833fdd67f7cb1f77ecc97/img/WhatsApp%20Image%202022-08-22%20at%2007.45.05%20(2).jpeg)
![Pokémon 3](https://github.com/diandrade/Pokedex-Challenge/blob/885ad43aa317ab55679afd46ac0d501964b99fee/img/WhatsApp%20Image%202022-08-22%20at%2007.45.05%20(1).jpeg)
![Pokémon 4](https://github.com/diandrade/Pokedex-Challenge/blob/cb67ea904f42e682957728ea821722d6d30ce1b1/img/WhatsApp%20Image%202022-08-22%20at%2007.45.06.jpeg)

Hello! This is the **Pokedex** project I created as part of a challenge, following the tutorial by YouTuber **Philipp Lackner**.

## Challenge Overview
The goal of the challenge was to create two lists:

### 1. Pokémon List
This list is populated by Pokémon fetched from the [Pokémon API](insert-link). Users can click on each Pokémon to view detailed information.

### 2. Saved Pokémon List
This list displays the Pokémon that the user has saved or marked as favorites.

## Pokémon Information
For each Pokémon, the following mandatory information is displayed:

- **ID**
- **Name**
- **Type** (grass, fire, water)
- **Photo**

Additionally, following Philipp's tutorial, we also include the following extra details:

- **Weight**
- **Height**
- **Stats**

## Technical Specifications
The following **technologies** and **design patterns** were used in the challenge:

- **MVVM** (Mandatory)
- **Room** (Mandatory)
- **Ktor** or **Retrofit** (Mandatory)
- **Coroutine** (Mandatory)
- **Jetpack Compose** (Optional)
- **Dependency Injection** (Optional)

## Challenges
Although I did a lot of research, several changes in app development technologies occurred since Philipp’s videos. As a result, I often had to research these changes, such as those in the Coil framework. Also, there were changes in the base project version, as well as the current versions of Gradle, Kotlin, and Hilt.

A notable challenge was creating the second list. Even after several attempts, I faced difficulties using **Room** with **Jetpack Compose**. I decided to focus on finishing the first list and adding the favorite feature as part of the next steps.
