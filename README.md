# IMAD511-ASSIGNMENT-TWO
The Dog Assistant Application is a tool designed to help dog owners manage their pets' daily needs. The application includes several features, including:
Feeding: The application can track when a dog was last fed and provide reminders to ensure that the dog is fed on a regular schedule.
Cleaning: The application can remind dog owners to clean up after their pets, including picking up waste and cleaning the dog's living area.
Hunger Checks: The application can help dog owners monitor their pets' hunger levels and provide recommendations for feeding based on the dog's age, weight, and activity level.
Happiness Checks: The application can provide dog owners with tips and advice for keeping their pets happy and healthy, including recommendations for exercise, playtime, and socialization.
This code is written in Kotlin and defines an Android activity for a hypothetical dog application. The activity is named DogApp2 and is a subclass of AppCompatActivity.
The activity has several private member variables that track the health, hunger, and cleanliness of a virtual pet. These variables are initialized to 100, 50, and 50, respectively.
The onCreate method is called when the activity is first created. It sets the layout for the activity and initializes several UI elements, including buttons and text views. It also sets the initial text values for the text views based on the current values of the petHealth, petHunger, and petCleanliness variables.
The onCreate method also sets up click listeners for the buttons. When the "feed" button is clicked, the petHunger variable is decreased by 10 and the petHealth variable is increased by 10. The petHunger variable is also increased by 5 to simulate the fact that feeding the pet will temporarily increase its hunger. The text views are then updated to reflect the new values of petHunger and petHealth. The animateImageChange function is also called to animate a change in the image view.
Similarly, when the "clean" button is clicked, the petCleanliness variable is increased by 10 and the petHealth variable is increased by 10. The text views are updated and the animateImageChange function is called.
When the "happy" button is clicked, the petHealth variable is increased by 10, and the petHunger and petCleanliness variables are both increased by 5. The text views are updated and the animateImageChange function is called.
The animateImageChange function takes an ImageView and a new image resource as arguments. It creates an AlphaAnimation object that fades the image view from fully transparent to fully opaque over a duration of 500 milliseconds. The fillAfter property is set to true to ensure that the image view remains fully opaque after the animation completes. The startAnimation method is called on the image view to start the animation, and the setImageResource method is called to set the new image.
The AlphaAnimation function is a constructor for the AlphaAnimation class that takes three arguments: a start alpha value, a duration, and a pivot value. However, this function is not used in the code and appears to be a placeholder for a future implementation.






