# Prettier Login Screen for Foundry VTT
Based on [code by u/bass-blowfish](https://www.reddit.com/r/FoundryVTT/comments/nmbq55/version_2_more_user_friendly_login_screen/), this simple, v0.8.x and v9 compatible CSS aims to make the login screen for worlds in [Foundry VTT](https://www.foundryvtt.com/) a little bit prettier by tidying up the interface and including custom logos.

The CSS can be applied by:
* copying the files in `img` to the `/resources/app/public/ui` folder;
* copying the file `foudry_login.css` file to the `/resources/app/public/css` folder;
* adding **at the top** of the `style.css` file in the `/resources/app/public/css` folder:
  ```css
  @import url("./foundry_login.css");
  ```
