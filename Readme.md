![Node](http://snag.gy/dEZ9e.jpg)

<span style="color:#008000"><strong>node</strong> /nōd/<br/>
Noun:
A point at which lines or pathways intersect or branch; a central or connecting point.</span>

After long being in development, and even longer in my head, finally I am happy to announce the release of **NODE**. For all those who have used my earlier launchers like [nDroid or 320mph](http://www.autohotkey.com/board/topic/2845-ndroid-formerly-320mph-ultra-fast-anything-launcher/), you will feel right at home with the blazing speed and ease of use.
(For those looking to cut to the chase, there's a very basic instruction set along with the download link just below)

It's also written with [AutoHotkey](http://http://www.autohotkey.com) - and has its own [discussion thread in AHK-forum](http://www.autohotkey.com/board/topic/79766-node-launcher-and-more/). 

And for those who would like to know more, here is **how Node is better** than what you have used earlier:

- The search algorithm is hugely enhanced. This will in effect find what you are looking for in a much better manner. The needed result will usually be in the top 3 matches, if not the first one. Yes, theoretically it can take longer to do all that ranking before presenting results than to just dump them, but there is a multitude of enhancements to reduce search time, and the end result's quality is a lot better.
- A well defined Object+Action relationship. Everything you search for in the first block are Objects, and depending on what you chose, the Actions are available. Now you can either press Enter to launch with the default action or press Tab and select the needed action. Simple.
- Ranking. All objects are ranked, some more than other. So if you used something recently, that gets ranked higher, readme files get ranked lower. And there are Top level Objects and Sub-Objects, so top level objects get ranked higher (but more on this later).
- Extensions. My favorite feature. Though AHK's limitations do not permit making plugins in their true sense (like you just dump a file in plugins folder, restart app and it becomes a part of the host), but still the way I've built it, it is very easy to write an extension for it. And extensions are very powerful here, they decide what is available to be searched, what part of it, what to show when a result is found, what actions are available and what gets done when that action is performed .. and lot more (details on this will come later too).
- The extensions can 'claim' a search. This means that once you enter something to be searched, the extensions (if so intended) can analyze the search and see if that is something they would like to interpret<br>
An example is the calculator functionality, where you just start typing a mathematical expression (without any prefix) and the calculator jumps in when it sees that it is something it understands.
- Looks better. Well, even at its first release, it looks better than my previous launchers 
 
## Basic Instructions: ##
1. Extract contents to a new folder.
2. Run Node.exe
3. Default hotkey is **Ctrl + /** to bring up the Object search.
4. Once you have found what you're looking for, press Enter to launch default action or press Tab to select another action.
5. Top level objects (like Clipboard) can be searched easily by typing / and their name

And this screenshot here will explain a some of the interface's properties:
![Node in Action](http://snag.gy/7fkpw.jpg)


## Ideology ##
The framework is based on Objects and Actions. You select an object, and then decide on an action to be performed on it. The most basic form of Object would be an application, and the simplest of Actions would be to open it. Then things start getting more interesting, another object can be clipboard text, and action can be remove formatting (so maybe you could paste it easily in GMail). Or an object can be a phrase you just typed, and action can be a web search or addition to Google Calendar.<br/>
Also, it learns and tries to best understand what you're looking for. For example, if you typed 'pad' and it brought up Notepad first, but you selected Wordpad, the next time you type 'pad' it brings up Wordpad first.</p>

Thank you