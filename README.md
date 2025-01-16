# RentaBot

RentaBot is an interactive chatbot designed to assist users in finding their ideal apartment or shared house within a specific apartment complex. The bot acts as a virtual assistant, asking relevant questions to understand user preferences and providing recommendations based on available housing options. The application is built using Python and leverages OpenAI's GPT-3.5-turbo for natural language processing. The graphical user interface (GUI) is created using the `panel` library, making the bot highly interactive and user-friendly.

---

## Features

- **Interactive Chat:** Guides users step-by-step to understand their housing preferences.
- **Dynamic Filtering:** Recommends apartments or shared houses based on user inputs like:
  - Number of bedrooms
  - Rental period (6 or 12 months)
  - Furnishing options (furnished or unfurnished)
  - Maximum budget
  - Desired amenities (e.g., parking, gym, garden, etc.)
  - Pet-friendliness
  - Preferred floor level
  - Move-in date
- **Friendly Recommendations:** If no exact matches are found, the bot suggests the closest available options.
- **Scheduling Tours:** Collects user email addresses to schedule tours for selected units.
- **Real-Time Interface:** Updates the conversation dynamically through a clean and intuitive interface.

---

## How It Works

1. The user starts by interacting with the chatbot through a simple input field.
2. The bot asks targeted questions to gather housing preferences step-by-step.
3. Based on user inputs, the bot filters available units and provides tailored recommendations.
4. Users can choose a unit, and the bot collects their email to schedule a tour.

---

## Example

Below are examples of a conversation with RentaBot:

Screenshot 1: Starting the conversation
![Panel Application - Page 1](images/Panel Application_Page_1.png)

Screenshot 2: Final recommendation
![Panel Application - Page 2](images/Panel Application_Page_2.png)

---

## Housing Units Data

The project includes a list of available housing options, each with detailed information about:

- Unit type (apartment/shared house)
- Number of bedrooms and bathrooms
- Monthly rent
- Rental periods
- Floor level
- Furnishing options
- Amenities
- Pet-friendliness
- Availability date

---

## Future Improvements

- Add support for more filtering options such as distance from specific locations or neighborhood preferences.
- Enhance the scheduling feature to integrate with calendar systems.
- Allow users to save their preferences for future searches.

---

## Contact

For questions or suggestions, feel free to contact [malmir.edumail@gmail.com].
