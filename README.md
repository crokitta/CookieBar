# Oracle APEX Region Plugin - rokit CookieBar

(based on: http://www.primebox.co.uk/projects/jquery-cookiebar/)

In 2012 the EU government decided it was necessary for every website available inside the EU to give visitors the option to allow or disable cookies.
This plug-in let's you include and configure such a notice within your APEX application.

## Changelog
#### 0.1 - Initial (beta) Release


## Install
- Import plugin file "region_type_plugin_nl_rokit_cookiebar.sql" from source directory into your application

## Plugin Settings
### Application Settings
The plugin settings are highly customizable and you can change:
- **Message** - 'We use cookies to track usage and preferences.', Message displayed on bar
- **Accept Button** - true,/Set to true to show accept/enable button
- **Accept Text** - 'I Understand', Text on accept/enable button
- **Accept JS Function** - JS function name to run after accept
- **Decline Button** - false, Set to true to show decline/disable button
- **Decline Text** - 'Disable Cookies', Text on decline/disable button
- **Decline JS Function** - JS function name to run after decline
- **Policy Button** - false, Set to true to show Privacy Policy button
- **Policy Text** - 'Privacy Policy', Text on Privacy Policy button
- **Policy URL** - URL of Privacy Policy
- **Expire** - true, Set to true for cookies to be accepted automatically. Banner still shows
### Component Settings
- **Force Show** - false, Force cookieBar to show regardless of user cookie preference

## How to use
- Create a APEX CookieBar region on target page (preferably page 0)
- Choose best fitting plugin attributes (help included)

## Custom CSS
This is the default CSS. Use these classes to overwrite and customize to your own design:

#cookie-bar {background:#111111; height:auto; line-height:24px; color:#eeeeee; text-align:center; padding:3px 0;}
#cookie-bar.fixed {position:fixed; top:0; left:0; width:100%;}
#cookie-bar.fixed.bottom {bottom:0; top:auto;}
#cookie-bar p {margin:0; padding:0;}
#cookie-bar a {color:#ffffff; display:inline-block; border-radius:3px; text-decoration:none; padding:0 6px; margin-left:8px;}
#cookie-bar .cb-enable {background:#007700;}
#cookie-bar .cb-enable:hover {background:#009900;}
#cookie-bar .cb-disable {background:#990000;}
#cookie-bar .cb-disable:hover {background:#bb0000;}
#cookie-bar .cb-policy {background:#0033bb;}
#cookie-bar .cb-policy:hover {background:#0055dd;}

## Demo Application


## Preview

---
