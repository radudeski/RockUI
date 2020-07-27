# RockUI
GUI for Rock : Reloaded

RockUI version 1.2.0

Special thanks goes out to Morbis from Rock : Reloaded and Akaya, Demonnic, Eraene, tdk1069, Quixote and
Vadi ( sorry if i missed anyone! )from the Mudlet Discord for all the things they've done for the Mudlet 
community and the help they've given me along this journey.

Thanks for deciding to give RockUI a try! At the moment all chat channels ( broadcasts, racial gossips,
hives, says and lets not forget shouts :) ) are captured in the same console. The "stat", "raise" and 
"expeek" results are captured in another console below the chat window but they are not live. They capture
the respective tables at login and everytime you call them. Theyre basically for a quick reference and to
fill in some space for the time being:). Both the chat and stat consoles have buffers so you can view the 
history if you'd like. Positive and negative effect timers are implemented. They only keep track of the 
initial spell at this time. For example, effects like poison and plague will not show cumulative time 
remaining if you move rather than just letting the effect run out. You will likely have to move the map
into GUI box 2 yourself after opening it. I'm sure there's more info I'd like to share at this time but 
i cant remember anything else atm xD. ALL feedback is welcome! I want to know what you guys like and what 
you dont like! Installation instructions are at the bottom of this document.

Installation Instructions:

1. Download the RockUIv1.2.0.mpackage zip file from https://github.com/radudeski/RockUI

2. Extract package into the destination file of your choice

3. Open Mudlet then open your Rock profile / connection.

4. Click on Toolbox > Package Manager OR click on the Package Manager button on the toolbar OR hit ALT+O

5. Click "send-text-to-all-games" then click uninstall. 

6. Repeat step 3 for each of these packages "deleteOldProfiles", "run-lua-code-v4", "echo" and "generic 
mapper". ( each of these will be reinstalled when you install the RockUI package )

7. Find "RockUIv1.2.0.mpackage" in the location that you chose in step 1

8. Drag and drop "RockUIv1.2.0.mpackage" ( as it is worded here, not the entire folder ) into the mudlet
window.

9. You should now see the RockUI on your Mudlet screen.

10. Hit the "X" on the top right to close Mudlet, when prompted click yes to save the profile.

11. Reopen Mudlet, sign into Rock and type "find prompt" to calibrate your position for the mapper.

12. You may want to adjust the size of your Mudlet window. If you go too small, youll know it.

13.You may also need to position the map manually. If this is the case make it short and about as wide as the 
box on the top right labeled "GUI.Box2". Align the bottom of the map window with the bottom of the GUI box
drop the map window then size vertically to the appropriate size ( if you dont do it this way it will try 
to auto-dock the map up top ).

12. ENJOY! :)
