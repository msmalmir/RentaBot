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

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/RentaBot.git
   cd RentaBot
