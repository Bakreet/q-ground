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

  * Users:

    * Users can register and log in to the system
    * Users can logout from the system
    * Users can manage their profile
    * Users can enable / disable 2FA
  * Admins:

    * Admins can log in to the system
    * Admins can logout from the system
    * Admins can manage all users account except admin
    * Admins must use 2FA
    * Every time an admin creates, edits, or deletes a user accounts, the system logs the action in the database
  * Super Admins:

    * Super admins can log in to the system
    * Super admins can logout from the system
    * Super admins can manage admin and super admin accounts
    * Super admins must use 2FA
    * Every time an super admins creates, edits, or deletes admin and super admin accounts, the system logs the action in the database
* Quiz Management

  * Quizzes have categories
  * Users:

    * Users can create quizzes
    * Users can edit and delete their own quizzes
    * Users can assign categories to quizzes they have created
    * Users can add leason materials to quizzes they have created  
  *Admins:

    * Admins can manage all quizzes
    * Every time an admins creates, edits, or deletes quizzes, the system logs the action in the database
* Quiz Visibility Settings

  * Quiz visibility can be set to:

    * Public
    * Private
    * Unlisted
* Quiz Structure \& Behavior

  * Quiz questions support:

    * Single answer
    * Multiple correct answers
    * Question with image
    * Answer with image
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
  * Admins can manage all leaderboard
  * Every time an admins creates, edits, or deletes leaderboard, the system logs the action in the database
* AI Learning Feature

  * AI-powered chat learning feature available before or after quiz
  * Users that own quiz can enable or disable AI learning feature
  * Admins can manage AI-related quiz features
  * Every time an admins manages AI-related quiz features, the system logs the action in the database
* Social Interaction

  * Users can:

    * Rate quizzes they have already played
    * Comment on quizzes they have already played
  * Comments display how many times the user has played the quiz
  * Admins can manage all rate and comment
  * Every time an admins creates, edits, or deletes rate and comment, the system logs the action in the database
* Quiz Discovery

  * Users can search for quizzes
  * Users can filter quizzes by category
* User Engagement Features

  * Users can:

    * Favorite quizzes
    * Save quizzes for later
  * Admins can manage all favorite and save quizzes
  * Every time an admins creates, edits, or deletes favorite and save quizzes, the system logs the action in the database
* User Activity Tracking:

  * Users have quiz play history
  * System stores past attempts and results
  * Admins can manage all quiz play history
  * Every time an admins creates, edits, or deletes quiz play history, the system logs the action in the database
* Super Admins:

  * Super admins can see log action
  * Super admins can search log action
  * Super admins can filter search log action
  * Super admins can export to PDF the last 20 log entries, selected log entries, or a combination of the last 20 and selected log entries
6. ### **Constraints**

