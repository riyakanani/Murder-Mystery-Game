# Murder-Mystery-Game
 Javascript Murder Mystery Game. 

<h2>Project Overview:</h2>
This is a murder mystery game where the player must solve multiple minigames in order to gain clues about who the murderer is. Run code at: https://editor.p5js.org/amazzone/sketches/tyN4KIrE5

<h2>My Contributions:</h2>

<h3>Screen Management:</h3>
Each screen function, like startScreen() and murdererScreen(), dynamically renders content such as text, images, and animations to set the game’s tone and narrative. I added interactive visuals and sound cues to enhance the atmosphere, including startScreen()'s animated title text and background image that fades in and out, creating a suspenseful first impression.

<h3>User Interaction & Navigation:</h3>
The mouseClicked() function handles flexible navigation, allowing players to move between screens by once they complete a task. I also implemented resetGame() to randomize critical game elements, ensuring varied gameplay with each reset.

<h3>Weapons Class and Particle System:</h3>
Designed a challenging "clicker game" where players must quickly click the correct weapon type amidst other moving weapons in a particle system. This minigame includes dynamic object creation and collision handling. The render() function dynamically displays each weapon’s image based on type, tinting colors as visual feedback for the player. I implemented a physics engine in collide() to manage interactions between weapons, ensuring they move naturally on the screen and respond accurately when clicked. I further supported the atmosphere by adding sound effects to heighten player engagement during gameplay.

