1. ### **Problem Definition**
* 
2. ### **Objectives**
* 
3. ### **Scope**
* 
4. ### **User Roles**
* Super Admin
* Admin
* User
5. ### **Feature List**
* User Management

  * Users can register and log in to the system
  * Users can manage their profile
  * Users can enable / disable 2FA
  * Admin can manage all users account except admin
  * Admin must use 2FA
  * Every time an admin creates, edits, or deletes a user accounts, the system logs the action in the database
* Quiz Management

  * Quizzes have categories
  * Users can create quizzes
  * Users can edit and delete their own quizzes
  * Users can assign categories to quizzes they have created
  * Admin can manage all quizzes
  * Every time an admin creates, edits, or deletes quizzes, the system logs the action in the database
* Quiz Visibility Settings

  * Quiz visibility can be set to:

    * Public
    * Private
    * Unlisted
* Quiz Structure \& Behavior

  * Quiz questions support:

    * Single answer
    * Multiple correct answers
  * Answers are displayed using a card-based UI
  * Questions and answers can be:

    * Randomized
    * Static (fixed order)
  * The system logs the number of times a user leaves the website during gameplay in the database
* Quiz Gameplay System

  * Users can play quizzes created by other users
  * Users can preview and play their own quizzes
  * Each question has a timer
  * Total quiz time is calculated from all question timers
  * Quiz includes scoring system
  * Quiz attempt settings:

    * Single attempt
    * Multiple attempts
* Quiz Result System

  * Users can view gameplay statistics for their quizzes
  * Users can view detailed information about the statistics
* Leaderboard System

  * Each quiz has a leaderboard
  * First attempt creates a new score entry
  * Additional attempts are recorded with labels (e.g., "second attempt", etc.)
  * Leaderboard is affected by quiz attempt settings
  * Users who preview and play their own quizzes do not generate scores on the leaderboard
  * The leaderboard shows the number of times a user leaves the website during gameplay
* AI Learning Feature

  * AI-powered chat learning feature available before or after quiz
  * User that own quiz can enable or disable AI learning feature
  * Admin can manage AI-related quiz features
  * Every time an admin manages AI-related quiz features, the system logs the action in the database
* Social Interaction

  * Users can:

    * Rate quizzes they have already played
    * Comment on quizzes they have already played
  * Comments display how many times the user has played the quiz
* Quiz Discovery

  * Users can search for quizzes
  * Users can filter quizzes by category
* User Engagement Features

  * Users can:

    * Favorite quizzes
    * Save quizzes for later
* User Activity Tracking

  * Users have quiz play history
  * System stores past attempts and results
* Super Admin

  * Super admins can manage admin and super admin accounts
  * Super admin must use 2FA
  * Every time an admin creates, edits, or deletes admin accounts, the system logs the action in the database
  * Super admin can see log action
  * Super admin can search log action
  * Super admin can filter search log action
  * Super admins can export to PDF the last 20 log entries, selected log entries, or a combination of the last 20 and selected log entries
6. ### **Constraints**

