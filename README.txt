Global settings (Page title, tab title, search bar) edited via config.toml
Links/icons and groupings edited via data/links.yml file
Icons are taken from FontAwesome-download svg file for icon you want, move it to
	~/quickstart/themes/bootstrap-bp-hugo-startpage/static/webfonts/ , reference it 
	in file as 'fa(style) fa-(icon name)' so for example Solid style, name chart-line
	will be referenced as 'fas fa-chart-line'

Background image is in /themes/bootstrap-bp-hugo-startpage/static/images/
Launch test server with 'hugo server -t bootstrap-bp-hugo-startpage' 
	-webpage will be available at localhost:1313
	-view this page with Xquartz or similar, open Firefox on server
	  and navigate to localhost:1313

Compile into static html file with 'hugo -D'
Output will be in ./public/ directory by default (-d/--destination flag to change it, or set publishdir in the config file).
Set nginx default page to open html file and webpage will be available at monitor.wrinternet.com
