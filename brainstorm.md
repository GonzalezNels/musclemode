# Brainstorming – Milestone 1

## Initial Brainstorming Ideas (6+ ideas)

1. **MuscleMode Lite – Workout Planner**
   - A simple workout planner that generates daily routines based on selected muscle groups and equipment (Gym/Home/No-Equipment). Users can mark exercises as completed and view recent workout history.

2. **WanderWise – Travel Itinerary Planner**
   - A trip planning app where users create trips, add day-by-day activities, and keep all their plans (food, hikes, attractions) in one structured itinerary instead of random notes/screenshots.

3. **SnackSaver – Food Expiration & Meal Helper**
   - Users log groceries with expiration dates. The app warns them when food is about to expire and suggests basic meal ideas using items they already have.

4. **StudyBuddy – Task & Study Session Scheduler**
   - A student-focused planner that schedules study blocks, breaks big assignments into smaller tasks, and tracks what’s due soon across classes.

5. **RecipeMatch – Cook from Ingredients**
   - Users input the ingredients they have at home, and the app suggests possible recipes and basic meal ideas, focusing on easy student-friendly dishes.

6. **EventHive – Local Hangout & Event Finder**
   - Helps small groups of friends find things to do nearby (events, coffee shops, parks), vote on ideas, and finalize a plan in one place.

---

## Evaluation of Top 3 Ideas

### 1. MuscleMode Lite – Workout Planner

**Problem it solves:**  
Beginners and casual lifters often go to the gym or work out at home without a structured plan. They don’t know which exercises to do or how to build a routine.

**Target users:**  
Beginner–intermediate gym-goers and home workout users who want simple, guided workouts.

**Pros:**
- Highly relatable and personally relevant (we already care about fitness).
- Very clear core loop: choose focus + equipment → generate workout → check off exercises.
- Easy to demo visually (lists of exercises, completion, history).
- App can start simple with static exercise data and grow later.

**Cons:**
- There are many fitness apps already, so it needs a focused, clean UX.
- Videos/GIFs and tracking weights are more advanced features (stretch, not MVP).

**Technical feasibility (for course timeline):**
- Feasible with simple backend or even static data at first.
- Data models are straightforward: Users, Workouts, Exercises, History.
- Good fit for incremental milestones (MVP now, more features later).

---

### 2. WanderWise – Travel Itinerary Planner

**Problem it solves:**  
Planning a trip is messy: people bounce between multiple tabs, maps, and notes. There’s no single clean place to store a day-by-day plan.

**Target users:**  
Students and young adults going on trips who want an organized itinerary.

**Pros:**
- Very visual and demo-friendly (trip cards, days, activities).
- Easy to understand: people know what an itinerary is.
- Can support cool features like maps, tags, and sharing later.

**Cons:**
- Some features like maps, external APIs, and sharing could get complicated if we go too deep.
- Harder to test without actual upcoming trips, but still demoable.

**Technical feasibility:**
- Core data (Trip, Days, Activities) is simple.
- MVP is just CRUD for trips and activities; maps/sharing can be stretch.

---

### 3. SnackSaver – Food Expiration & Meal Helper

**Problem it solves:**  
People waste food and money because they forget what’s in their fridge and when it expires.

**Target users:**  
Students and busy adults who cook sometimes and forget about groceries.

**Pros:**
- Very focused problem with clear use cases (add food, see “expiring soon”).
- Great for simple notifications/list views.
- Can integrate later with recipe suggestions.

**Cons:**
- Real value depends on users consistently logging items.
- Recipe recommendation logic can get complex if we go beyond simple suggestions.

**Technical feasibility:**
- Basic CRUD (items + dates) is easy.
- “Expiring soon” view is just sorting/filtering by date.
- Recipe suggestions can be very simple (keyword-based) or left as stretch features.

---

## Final App Idea Chosen

### ✅ Final Choice: MuscleMode Lite – Workout Planner

We are choosing **MuscleMode Lite** as our final app idea.

**Reasons for choosing MuscleMode Lite:**
- Strong personal relevance and motivation to use it ourselves.
- Very clear MVP: select workout type + equipment → generate list of exercises → mark them done.
- The app fits well within the course timeline and milestone structure.
- It has room for growth (favorites, difficulty levels, history, GIFs/videos) without blocking the initial version.
- Easy to demo in a short video: open app, choose settings, see generated workout, check off exercises.

**One-sentence description:**  
**MuscleMode Lite** is a simple workout planner that generates daily routines based on your workout focus and equipment, letting you follow and complete structured workouts without overthinking what to do.
