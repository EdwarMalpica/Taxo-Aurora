
Files:

 - lib/utils.ts
 - components/theme-provider.tsx
 - components/celebration-animation.tsx
 - components/cup-selector.tsx
 - components/water-tracker.tsx
 - components/water-visualization.tsx
 - components/water-history.tsx
 - components/toaster.tsx
 - hooks/use-toast.ts
 - hooks/use-local-storage.ts
 - hooks/use-mobile.tsx
 - app/layout.tsx
 - app/page.tsx

Message before the each file:

File: lib/utils.ts

Message:
First, let's create a utility file to store common functions and constants that we'll use throughout the project. This file will help us keep our code organized and maintainable.

File: components/theme-provider.tsx

Message:
Next, let's create a ThemeProvider component that will handle the theme context for our application. This component will allow us to switch between light and dark themes easily.

File: components/celebration-animation.tsx

Message:
Now, let's create a CelebrationAnimation component that will display fun animations when the user reaches their daily water intake goal. This component will add an element of gamification to the water intake tracking experience.

File: components/cup-selector.tsx

Message:
Next, let's create a CupSelector component that will allow users to select the size of the cup they are using to track their water intake. This component will provide a visual representation of the cup size and make it easy for users to track their progress.

File: components/water-tracker.tsx

Message:
Now, let's create a WaterTracker component that will display the user's daily water intake progress and provide feedback on their goal achievement. This component will help users stay motivated and hydrated throughout the day.

File: components/water-visualization.tsx

Message:
Next, let's create a WaterVisualization component that will visually represent the user's water intake progress. This component will provide a clear and intuitive way for users to track their daily water consumption.

File: components/water-history.tsx

Message:
Now, let's create a WaterHistory component that will display the user's water intake history and achievements. This component will allow users to track their progress over time and celebrate their milestones.

File: components/toaster.tsx

Message:
Next, let's create a Toaster component that will display toast notifications for user actions and alerts. This component will provide feedback to users and enhance the user experience.

File: hooks/use-toast.ts

Message:
Now, let's create a custom hook called useToast that will handle toast notifications in our application. This hook will simplify the process of displaying notifications and make it easy to provide feedback to users.

File: hooks/use-local-storage.ts

Message:
Next, let's create a custom hook called useLocalStorage that will handle reading and writing data to local storage. This hook will allow us to persist user data across sessions and provide a seamless experience.

File: hooks/use-mobile.tsx

Message:
Now, let's create a custom hook called useMobile that will detect the user's device type and screen size. This hook will help us optimize the layout and user experience for different devices.

File: app/layout.tsx

Message:
Next, let's update the Layout component to include the new components we've created. This component will serve as the main layout for our application and provide a consistent structure for our pages.

File: app/page.tsx

Message:
Finally, let's update the Page component to include the new components and hooks we've created. This component will serve as the main page template for our application and help us organize our content effectively.`;



------------------------------------------------------------------------------------------------

# Prompt:
Build a React/TypeScript web app that allows users to search for movies, view details, and write reviews. 

Files:

 - lib/utils.ts
 - lib/mock-data.ts
 - components/theme-provider.tsx
 - components/movie-thumbnails.tsx
 - components/movie-card.tsx
 - components/navbar.tsx
 - components/review-form.tsx
 - components/footer.tsx
 - components/movie-grid.tsx
 - components/search-form.tsx
 - components/sonner-provider.tsx
 - components/review-list.tsx
 - hooks/use-toast.ts
 - hooks/use-mobile.tsx
 - app/layout.tsx
 - app/page.tsx
 - app/loading.tsx
 - app/movies/[id]/page.tsx

Message before the each file:

File: lib/utils.ts
Message: First, let's create a utility file to store common functions and constants that we'll use throughout the project. This file will help us keep our code organized and maintainable.

File: lib/mock-data.ts
Message: Next, let's create a mock data file to simulate movie data that we'll use for testing and development. This file will provide sample movie information for our application.

File: components/theme-provider.tsx
Message: Now, let's create a ThemeProvider component that will handle the theme context for our application. This component will allow us to switch between light and dark themes easily.

File: components/movie-thumbnails.tsx
Message: Next, let's create a MovieThumbnails component that will display a grid of movie thumbnails for users to browse. This component will provide a visual overview of available movies and help users navigate the movie collection.

File: components/movie-card.tsx
Message: Now, let's create a MovieCard component that will display detailed information about a movie. This component will show movie details such as title, poster, rating, and description.

File: components/navbar.tsx
Message: Next, let's create a Navbar component that will serve as the navigation bar for our application. This component will provide links to different sections of the app and help users navigate between pages.

File: components/review-form.tsx
Message: Now, let's create a ReviewForm component that will allow users to write and submit reviews for movies. This component will provide a form for users to input their review and submit it for display.

File: components/footer.tsx
Message: Next, let's create a Footer component that will display additional information and links at the bottom of the page. This component will provide contact information, social media links, and other relevant details.

File: components/movie-grid.tsx
Message: Now, let's create a MovieGrid component that will display a grid of movie cards for users to browse. This component will show movie details in a visually appealing layout and allow users to view more information about each movie.

File: components/search-form.tsx
Message: Next, let's create a SearchForm component that will allow users to search for movies by title. This component will provide a search input field and a submit button for users to find movies easily.

File: components/sonner-provider.tsx
Message: Now, let's create a SonnerProvider component that will handle the sonner context for our application. This component will allow us to switch between different sonner themes easily.

File: components/review-list.tsx
Message: Next, let's create a ReviewList component that will display a list of reviews for a specific movie. This component will show user reviews, ratings, and comments for each movie.

File: hooks/use-toast.ts
Message: Now, let's create a custom hook called useToast that will handle toast notifications in our application. This hook will simplify the process of displaying notifications and make it easy to provide feedback to users.

File: hooks/use-mobile.tsx
Message: Next, let's create a custom hook called useMobile that will detect the user's device type and screen size. This hook will help us optimize the layout and user experience for different devices.

File: app/layout.tsx
Message: Next, let's update the Layout component to include the new components we've created. This component will serve as the main layout for our application and provide a consistent structure for our pages.

File: app/page.tsx
Message: Now, let's update the Page component to include the new components and hooks we've created. This component will serve as the main page template for our application and help us organize our content effectively.

File: app/loading.tsx
Message: Next, let's create a Loading component that will display a loading spinner while fetching data. This component will provide visual feedback to users and improve the user experience during data loading.

File: app/movies/[id]/page.tsx
Message: Finally, let's create a dynamic movie details page that will display detailed information about a specific movie. This page will show movie details, reviews, and related content based on the movie ID in the URL.


------------------------------------------------------------------------------------------------

# Prompt:
Build a React/TypeScript web app that allows users to search for movies, view details, and write reviews. 

Files:

 - lib/date-utils.ts
 - lib/utils.ts
 - types/task.ts
 - components/theme-provider.tsx
 - components/recent-tasks.tsx
 - components/family-progress.tsx
 - components/global-alert-dialog.tsx
 - components/theme-toggle.tsx
 - components/create-task-modal.tsx
 - components/overview.tsx
 - hooks/use-mobile.tsx
 - contexts/alert-dialog-context.tsx
 - contexts/task-context.tsx
 - app/layout.tsx
 - app/page.tsx
 - app/loading.tsx
 - app/family/page.tsx

Message before the each file:

File: lib/date-utils.ts
Message: First, let's create a utility file to handle date-related functions and constants that we'll use throughout the project. This file will help us manage dates, times, and time zones effectively.

File: lib/utils.ts
Message: Next, let's create a utility file to store common functions and constants that we'll use throughout the project. This file will help us keep our code organized and maintainable.

File: types/task.ts
Message: Now, let's create a type file to define the Task type that we'll use to represent tasks in our application. This file will help us ensure type safety and consistency when working with tasks.

File: components/theme-provider.tsx
Message: Now, let's create a ThemeProvider component that will handle the theme context for our application. This component will allow us to switch between light and dark themes easily.

File: components/recent-tasks.tsx
Message: Next, let's create a RecentTasks component that will display a list of recently completed tasks. This component will help users track their progress and stay motivated.

File: components/family-progress.tsx
Message: Now, let's create a FamilyProgress component that will display the progress of family members in completing tasks. This component will provide a visual overview of family achievements and encourage collaboration.

File: components/global-alert-dialog.tsx
Message: Next, let's create a GlobalAlertDialog component that will display global alert messages for important notifications. This component will provide a consistent way to show alerts and messages to users.

File: components/theme-toggle.tsx
Message: Next, let's create a ThemeToggle component that will allow users to switch between light and dark themes. This component will provide a visual indicator of the current theme and allow users to customize their experience.

File: components/create-task-modal.tsx
Message: Now, let's create a CreateTaskModal component that will allow users to create new tasks. This component will provide a form for users to input task details and add tasks to the task list.

File: components/overview.tsx
Message: Next, let's create an Overview component that will display an overview of tasks and progress. This component will show task statistics, progress charts, and other relevant information.

File: hooks/use-mobile.tsx
Message: Now, let's create a custom hook called useMobile that will detect the user's device type and screen size. This hook will help us optimize the layout and user experience for different devices.

File: contexts/alert-dialog-context.tsx
Message: Next, let's create an AlertDialogContext provider that will manage the state and actions related to alert dialogs. This context will allow components to display alert messages and notifications.

File: contexts/task-context.tsx
Message: Next, let's create a TaskContext provider that will manage the state and actions related to tasks. This context will allow components to access and update task data across the application.

File: app/layout.tsx
Message: Next, let's update the Layout component to include the new components we've created. This component will serve as the main layout for our application and provide a consistent structure for our pages.

File: app/page.tsx
Message: Now, let's update the Page component to include the new components and hooks we've created. This component will serve as the main page template for our application and help us organize our content effectively.

File: app/loading.tsx
Message: Next, let's create a Loading component that will display a loading spinner while fetching data. This component will provide visual feedback to users and improve the user experience during data loading.

File: app/family/page.tsx
Message: Finally, let's create a Family page that will display family tasks and progress. This page will show family achievements, task lists, and progress charts based on the family context.



------------------------------------------------------------------------------------------------

# Prompt:
Create a React app that contains a carbon footprint calculator with simple lifestyle questions and visual impact representation

Files:

 - lib/utils.ts
 - lib/types.ts
 - lib/carbon-calculations.ts
 - components/theme-provider.tsx
 - components/carbon-calculator.tsx
 - components/results-visualization.tsx
 - components/theme-toggle.tsx
 - components/forms/home-energy-form.tsx
 - components/forms/food-consumption-form.tsx
 - components/forms/transportation-form.tsx
 - app/layout.tsx
 - app/page.tsx

Message before the each file:

File: lib/utils.ts
Message: First, let's create a utility file to store common functions and constants that we'll use throughout the project. This file will help us keep our code organized and maintainable.

File: lib/types.ts
Message: Next, let's create a types file to define the types and interfaces that we'll use in our project. This file will help us ensure type safety and consistency in our code.

File: lib/carbon-calculations.ts
Message: Now, let's create a file to handle carbon footprint calculations based on user inputs. This file will contain functions to calculate carbon emissions from lifestyle choices.

File: components/theme-provider.tsx
Message: Now, let's create a ThemeProvider component that will handle the theme context for our application. This component will allow us to switch between light and dark themes easily.

File: components/carbon-calculator.tsx
Message: Next let's create a CarbonCalculator component that will display lifestyle questions and calculate the user's carbon footprint. This component will provide a visual representation of the user's environmental impact.

File: components/results-visualization.tsx
Message: Now, let's create a ResultsVisualization component that will display the user's carbon footprint and environmental impact visually. This component will show the user's carbon emissions in a clear and engaging way.

File: components/theme-toggle.tsx
Message: Next, let's create a ThemeToggle component that will allow users to switch between light and dark themes. This component will provide a visual indicator of the current theme and allow users to customize their experience.

File: components/forms/home-energy-form.tsx
Message: Now, let's create a HomeEnergyForm component that will collect user input on home energy consumption. This component will ask questions about energy usage and calculate the carbon footprint based on the user's responses.

File: components/forms/food-consumption-form.tsx
Message: Next, let's create a FoodConsumptionForm component that will collect user input on food consumption habits. This component will ask questions about diet choices and calculate the carbon footprint based on the user's responses.

File: components/forms/transportation-form.tsx
Message: Now, let's create a TransportationForm component that will collect user input on transportation choices. This component will ask questions about travel habits and calculate the carbon footprint based on the user's responses.

File: app/layout.tsx
Message: Next, let's update the Layout component to include the new components we've created. This component will serve as the main layout for our application and provide a consistent structure for our pages.

File: app/page.tsx
Message: Finally, let's update the Home component to include the new components we've created. This component will serve as the main page template for our application and help us organize our content effectively.


------------------------------------------------------------------------------------------------

# Prompt:
Create a meal portion visualizer using React/TypeScript that shows proper serving sizes using common household objects

Files:

 - lib/portion-data.ts
 - lib/utils.ts
 - components/theme-provider.tsx
 - components/food-category-icon.tsx
 - components/portion-card.tsx
 - components/meal-portion-visualizer.tsx
 - components/portion-visualizer.tsx
 - components/theme-toggle.tsx
 - app/layout.tsx
 - app/page.tsx

Message before the each file:

File: lib/portion-data.ts
Message: First, let's create a portion data file to store information about common household objects used for portion visualization. This file will help us provide accurate and consistent serving size references.

File: lib/utils.ts
Message: Next, let's create a utility file to store common functions and constants that we'll use throughout the project. This file will help us keep our code organized and maintainable.

File: components/theme-provider.tsx
Message: Now, let's create a ThemeProvider component that will handle the theme context for our application. This component will allow us to switch between light and dark themes easily.

File: components/food-category-icon.tsx
Message: Next, let's create a FoodCategoryIcon component that will display icons representing different food categories. This component will help users identify food groups easily.

File: components/portion-card.tsx
Message: Now, let's create a PortionCard component that will display information about a specific portion size. This component will show the name, description, and visual representation of the portion.

File: components/meal-portion-visualizer.tsx
Message: Next, let's create a MealPortionVisualizer component that will visualize meal portions using common household objects. This component will help users understand proper serving sizes and portion control.

File: components/portion-visualizer.tsx
Message: Now, let's create a PortionVisualizer component that will display a visual representation of portion sizes using common household objects. This component will provide an interactive and informative way to visualize serving sizes.

File: components/theme-toggle.tsx
Message: Next, let's create a ThemeToggle component that will allow users to switch between light and dark themes. This component will provide a visual indicator of the current theme and allow users to customize their experience.

File: app/layout.tsx
Message: Next, let's update the Layout component to include the new components we've created. This component will serve as the main layout for our application and provide a consistent structure for our pages.

File: app/page.tsx
Message: Finally, let's update the Page component to include the new components we've created. This component will serve as the main page template for our application and help us organize our content effectively.


------------------------------------------------------------------------------------------------

# Prompt:
Create a family task and chore management system with recurring tasks and progress visualization for multiple household members.

Files:
 - types.tsx
 - lib/date-utils.ts
 - lib/utils.ts
 - types/task.ts
 - components/theme-provider.tsx
 - components/recent-tasks.tsx
 - components/family-progress.tsx
 - components/global-alert-dialog.tsx
 - components/task-modal.tsx
 - components/theme-toggle.tsx
 - components/overview.tsx
 - contexts/alert-dialog-context.tsx
 - contexts/task-context.tsx
 - app/layout.tsx
 - app/page.tsx
 - app/loading.tsx
 - app/family/page.tsx


Message before the each file:

File: types.tsx
Message:
First, let's create a types file to define the types and interfaces that we'll use in our project. This file will help us ensure type safety and consistency in our code.

File: lib/date-utils.ts
Message:
Next, let's create a utility file to handle date-related functions and constants that we'll use throughout the project. This file will help us manage dates, times, and time zones effectively.

File: lib/utils.ts
Message:
Now, let's create a utility file to store common functions and constants that we'll use throughout the project. This file will help us keep our code organized and maintainable.

File: types/task.ts
Message:
Next, let's create a type file to define the Task type that we'll use to represent tasks in our application. This file will help us ensure type safety and consistency when working with tasks.

File: components/theme-provider.tsx
Message:
Now, let's create a ThemeProvider component that will handle the theme context for our application. This component will allow us to switch between light and dark themes easily.

File: components/recent-tasks.tsx
Message:
Next, let's create a RecentTasks component that will display a list of recently completed tasks. This component will help users track their progress and stay motivated.

File: components/family-progress.tsx
Message:
Now, let's create a FamilyProgress component that will display the progress of family members in completing tasks. This component will provide a visual overview of family achievements and encourage collaboration.

File: components/global-alert-dialog.tsx
Message:
Next, let's create a GlobalAlertDialog component that will display global alert messages for important notifications. This component will provide a consistent way to show alerts and messages to users.

File: components/task-modal.tsx
Message:
Now, let's create a TaskModal component that will allow users to view and edit task details. This component will provide a modal interface for managing task information.

File: components/theme-toggle.tsx
Message:
Next, let's create a ThemeToggle component that will allow users to switch between light and dark themes. This component will provide a visual indicator of the current theme and allow users to customize their experience.

File: components/overview.tsx
Message:
Now, let's create an Overview component that will display an overview of tasks and progress. This component will show task statistics, progress charts, and other relevant information.

File: contexts/alert-dialog-context.tsx
Message:
Next, let's create an AlertDialogContext provider that will manage the state and actions related to alert dialogs. This context will allow components to display alert messages and notifications.

File: contexts/task-context.tsx
Message:
Next, let's create a TaskContext provider that will manage the state and actions related to tasks. This context will allow components to access and update task data across the application.

File: app/layout.tsx
Message:
Next, let's update the Layout component to include the new components we've created. This component will serve as the main layout for our application and provide a consistent structure for our pages.

File: app/page.tsx
Message:
Finally, let's update the Home component to include the new components we've created. This component will serve as the main page template for our application and help us organize our content effectively.

File: app/loading.tsx
Message:
Next, let's create a Loading component that will display a loading spinner while fetching data. This component will provide visual feedback to users and improve the user experience during data loading.

File: app/family/page.tsx
Message:
Finally, let's create a Family page that will display family tasks and progress. This page will show family achievements, task lists, and progress charts based on the family context.
