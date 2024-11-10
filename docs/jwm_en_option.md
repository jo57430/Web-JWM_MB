<img src="assets/logo_long.png" alt="Logo du script 'JWM-MB'" width="25%"/>

# [J-BAUER][EN] Jo Windows Manager : MessageBox Add-on

> **By Jonathan BAUER (J-BAUER)**</br>
> Version: 1.0</br>
> Date: 10/11/2024


## List of the available option for `JWM.newMessagebox` or `JWM.newMessageboxReponse`
When you create a new instance of a MessageBox it is possible to pass options to change its behavior.
All the options in `JWM_Window` are available and can be used here in addition to those below.

### callback [def: ()=>{}]
Used to set the function called back when the user has made a choice.

### timeout [def: 0]
Close the window after x ms if any action has been taken.

### winman_identifier [def: null]
Used to set witch WindowManager to use, by is unique identifier.

### win_identifier [def: null]
Used to set the unique identifier of the window.

### customIcon [def: ""]
Used to set a custom icon when 'int_iconType' is 5 [exemple: "url("https://raw.githack.com/jo57430/Web-JWM/refs/heads/master/lib/assets/icons/restore.svg")"]
