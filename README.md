# mac-env
my macbook's system preferences and environment setup and configuration


this is to setup the initial system preference and environment setup and configuration.

first to set up home brew:

open the terminal, and execute the below script to configure almost all settings in system preferences and finder configuration.
/bin/zsh -c "$(curl -fsSL https://raw.githubusercontent.com/subicura/settings/main/macos/system_setting.zsh)"

after executing above, you must restart the mac to relfect the changes you made. you can check the detail in the below address:
https://github.com/subicura/settings/blob/main/macos/system_setting.zsh

kor)
자동 설정 스크립트
macOS는 각종 설정을 보통 ~/Library/Preferences 폴더에 .plist 파일로 관리합니다. 시스템 및 파인더 설정도 동일한 방식을 사용하고 defaults 명령어로 설정할 수 있기 때문에 스크립트로 자동화 할 수 있습니다.

additional modification
unfortunately, you cannot customize all the setups you want through the above autoscript.
you must do the below three items by youself

system preferences - language and region
https://subicura.com/mac/setup/#언어-및-지역-language-region
keyboard > text: turn off all the auto-correction 
language & region 

system preferences - security
finder preferences - download folder option 


main manual:
https://subicura.com/mac/setup/setting.html#스크립트-실행

for reference:
https://blog.gangnamunni.com/post/brew_cask_mas/
