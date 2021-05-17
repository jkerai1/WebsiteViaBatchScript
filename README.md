# WebsiteViaBatchScript
Open a website using batch

Can open multiple tabs in the same window and specify which browser to open with, unlike dragging links to the desktop.

e.g to open DuckDuckGo and Youtube:

  START %BROWSER% -new-tab "https://duckduckgo.com/"
  START %BROWSER% -new-tab "https://youtube.com/"
	
	
	open with edge:
	
	SET BROWSER=msedge.exe
