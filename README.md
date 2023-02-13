# Introduction

This project is a static website for the ding & duer' secret notes.

# Dependency

* hugo
* git

# Usage

1. Clone repo to local machine

	```
	git clone https://github.com/wind-waves/520.git
	```
2. Update submodule for the hugo template (important!)
	```
	cd 520
	git submodule update --init --recursive
	```
3. Install [hugo](https://gohugo.io/installation/)

4. Add new note

	```
	vim content/records/xxx.md
	then edit the markdown file to add contents.
	```

5. Compile the project use hugo (note to execute hugo in project dir)
	```
	hugo
	```
6. Preview updates locally
	```
	hugo server -D
	chrome http://localhost:1313/520
	```
7. Upload changes

	```
	git commit -m "Add xxx note"
	git push origin main
	```
8. Check final result
	Wait for minutes and check http://www.dingloveduer.top
