# Learn Through

The Learn Through website is a landing page for a language learning platform which provides users flexible learning schedule and fittable learning material. Learn Through uses the modern technology of AI, to enhance the learning experience, thus, ensures the users to learning the desired language at anytime, anywhere and any way.

Users will be able to find the main features of the platform: AI-driven conversation, up-to-date news, learning group and practice with native speakers. Users can read somes comments from other users who have registered on the platform. Users have the possibility to sign up by the platform.

## Features

- Navigation
    - Featured at the top of the page, navigation shows the platform name in the left corner: LEARN THROUGH that links to the top of the page.
    - The other navigation links are to the right: Start Learning, Login and Sign Up which should link to separate page.
        - Start Learning should direct the user to select the disired language, level. (Currently not implemented yet)
        - Login should direct the user to a login page. (Currently not implemented yet)
        - Sign Up should direct the user to a sign up page. (Currently not implemented yet)
    - The position of navigation is set to be fix so that the users can always have the possibility to reach the next pages.
    ![A screenshot of the navigation](/assets/images/README/nav.png)

- The Header
    - The header shows the most important feature of the learning platform that "driven by the AI".
    - The header tells the users that the platform aims to provide a flexible and customized learning experience using the AI technology.
    - The header provides a link for the users to select the disired language, level (same as the Start Learning in the navigiation, which is currently not implemented yet).
    - The headers contains a image that clearly shows it is language learning platform.
    ![A screenshot of the header](/assets/images/README/header.png)

- The Feature Section
    - The feature section lists 4 main features that makes the platform special:
        - AI-driven conversation, which tells the users that the platform uses heavily AI technology to provide the users conversation with all scenarios.
        - Up-to-date news, which tells the users that the platform provides update-to-date-news written in a level that fits to the user, instead of providing the traditional text books.
        - Learning group, which tells the users that the users can create or join a learning group on the platform directly.
        - Talk to native speakers, which tells the users that the platform provides a lot of qualified native speakers.
    ![A screenshot of the feature section](/assets/images/README/feature.png)

- The Video Section
    - The video section contains a youtube video, that explains the user how AI can enhance the language learning experience. (The video should be ultimately created by Learn Through, apparently there is no such a material yet, and therefore, a relevant youtube video is being used.)
    ![A screenshot of the video section](/assets/images/README/video.png)

- The Comment Section
    - The comment section allows the users to review some of the comments from the students who have already registered and used the platform. So that the users know better how Learn Through can help and what is special at Learn Through.
    ![A screenshot of the comment section](/assets/images/README/comment.png)

- The Footer
    - The footer contains again the logo of the platform.
    - The footer contains again a clickable anchor that directs the user to the next page where they should select the desired language and level (currently not implemented yet).
    - The footer contains the social media links of the platform, facebook, twitter, youtube, instagram. (As of there is no official link yet, the landing page of each is being used)
    ![A screenshot of the footer](/assets/images/README/footer.png)

## Testing

- I tested and confirmed that the page works in browsers: Chrome, Firefox.
- I confirm that this project is responsive.

## Bugs

### Solved bugs
- When the screen width is smaller as 950px, the anchor element in the header is not clickable.
    - The issue is that the hero image overlaps with the anchor. To solve, z-index: 1 is being added to the style for this anchor element.
    ```
    #hero-text {
        top: 20%;
        left: 50%;
        transform: translate(-50%, -20%);
        clear: left;
        z-index: 1;
    }
    ```