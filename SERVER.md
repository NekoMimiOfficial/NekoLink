# Server API  

account low level endpoints  
- `api/login`: username+2fa -> token  
- `api/register`: invite_id+username -> auth_key+token  
- `api/logout`  

profile vanity setting endpoints  
- `api/vanity/pfp`  
- `api/vanity/banner`  
- `api/vanity/display_name`  
- `api/vanity/bio`  
- `api/vanity/profile_color`  
- `api/vanity/display_font`  
- `api/vanity/badge`  

getter endpoints  
- `api/get/profile`  
- `api/get/circle`  
- `api/get/channel`  
- `api/get/meows`  
- `api/get/emotes`  

account announce ws  
- `ws/status`  
- `ws/ping`  
- `ws/activity`  

file bucket  
- `api/files/upload`  
- `api/files/get`  
- `api/files/delete`  

account related endpoints  
- `api/account/reset_auth`  
- `api/account/delete`  

badge related endpoints  
- `api/badge/create`  
- `api/badge/delete`  
- `api/badge/assign`  
- `api/badge/strip`  
- `api/badge/update`  

emoji related endpoints  
- `api/emoji/create`  
- `api/emoji/delete`  
- `api/emoji/update`  
