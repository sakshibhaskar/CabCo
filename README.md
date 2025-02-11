Description
Usually, after exams or when the mid-sem break begins, there is a large surge of people going back to their respective hometown by air/railways. This journey involves an initial travel where the person takes a cab to the IGI Airport or the New Delhi Railway station. A lot of times, people are forced to travel solo, if there isn't anyone he/she knows traveling at a similar time. Also, this leads to shortage of cabs nearby and increase in waiting time. Had there been a student of NIT-D with whom the cab could have been shared, the fares would also be split and the waiting time will also reduce. Another thing is that girls prefer not to travel alone in Cabs in Delhi, so that problem will also be solved by this app.



Directory Layout
 CabCo
   +--- README, LICENSE // basic information
   +--- assets  // contains all assets like images for project
   |
   +--- lib
        +--- models
          +--- alltrips.dart // (WILL BE REMOVED LATER)
          +--- requestdetails.dart // Request Model
          +--- user.dart // User Model
        +--- screens
          +--- authenticate
            +--- authenticate.dart // for toggling between sign in and register
            +--- forgotpass.dart // forgot password screen
            +--- register.dart // register user screen
            +--- sign_in.dart // sign in screen
            +--- verified_email_check.dart // check if user verified screen
          +--- chatscreen // handles the chating section
            +--- chat_database
              +--- chatservices.dart
              +--- database.dart
            +--- chat_widgets
              +--- chat_bubbles.dart
              +--- chat_tile.dart
              +--- chat_users_list.dart
              +--- message.dart
              +--- new_message.dart
            +--- chat_screen.dart
          +--- groupdetailscreen // handles the screen when user clicks on a card on dashboard
            +--- appbar.dart // group details page appbar
            +--- ended_group_details.dart // group details page for ended rides
            +--- groupdetails.dart // group details page
          +--- groupscreen // handles the screen when user is in a cab/group
            +--- group.dart // shows the current group details
            +--- editgroup.dart // edit group details page
          +--- notifications // handles notification screen
            +--- services
              +--- database.dart // handles database for notifications
              +--- notifservice.dart // service file for calling database functions relevant to notifications
            +--- widgets
              +--- notifslist.dart // displays list of notifications
              +--- notiftile.dart // UI for notification tile
            +--- notifications.dart // notification page
          +--- profile
            +--- userprofile.dart // handles user profile screen
          +--- requests // handles the requests of users screen
            +--- myrequests.dart // displays Ended rides
          +--- createtrip.dart // the screen for creating a new group
          +--- dashboard.dart // handles dashboard
          +--- edituserdetails.dart // handles edit user details page
          +--- filter.dart // handles filter service
          +--- help.dart // handles help/FAQ screen
          +--- messages.dart // messages screen
          +--- rootscreen.dart // handles navigation services
          +--- settings.dart // settings page to set dark mode
          +--- tripslist.dart // displays the list of trips on dashboard
          +--- wrapper.dart // handles the routing when a user is logged in
        +--- services
          +--- auth.dart // handles all authentication related services
          +--- database.dart // the PRIMARY database service which handles everything
          +--- trips.dart // for calling a function purposes
        +--- shared
          +--- loading.dart // the loading screen
        +--- main.dart
   |
   +--- functions  // Firebase Functions Folder: automatically run backend code in response to events
   |               // triggered by Firebase features and HTTPS requests
   |
   +--- etc

