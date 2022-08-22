Simple patch to foundry screen for use with felddy dockerfile and container patch urls.

Follows idea from here: https://www.reddit.com/r/FoundryVTT/comments/o93x4y/loging_screen_modding_088/

To use, add 

CONTAINER_PATCH_URLS: 'https://raw.githubusercontent.com/shukerrjp/foundry-login/main/login-screen-patch.sh' as docker env.