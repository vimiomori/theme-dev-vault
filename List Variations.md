---
tags: meta
cssClass: wide-page
---

# List Variations

+ dataview
	```dataview
	list
	```
+ normal list
  - Marker character change forces new list start:
	- test
	- test
	- test
	- test
	- test
	- test
	- test
+ Tasks
	- [ ] one
		- [ ] nested
	- [ ] two
	- [ ] three
+ ordered
	1. test
	2. test
		1. test
			1. test
			2. test
	3. another
	4. last


With longer text that wraps: 

- *Longer item with wrapped text.* Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
	- Second level  
		*Additional paragraph after line break.* Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
		- Third level
			- Fourth level
	- Second level #2
		- Third level
			- Fourth level

## Ordered lists
Simple numeric list

1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa

1. You can use sequential numbers...
1. ...or keep all the numbers as `1.`

Start numbering with offset:

57. foo
1. bar

Nested numbered lists

- test
	- test
		- test
			- test
				- test
					- test
						- test

1. Lorem ipsum dolor sit amet, consectetur 
	1. adipiscing elit, 
		1. sed do eiusmod tempor incididunt 
			1. ut labore et dolore magna aliqua. 
				1. test
					1. test
						1. test
							1. test
								1. test
									1. test
		2. Ut enim ad minim veniam, quis nostrud 
	2. exercitation ullamco laboris nisi ut 
2. aliquip ex ea commodo consequat

Mixed numbered lists

1. Lorem ipsum dolor sit amet, consectetur 
	- adipiscing elit, 
		1. sed do eiusmod tempor incididunt 
			- ut labore et dolore magna aliqua. 
		2. Ut enim ad minim veniam, quis nostrud 
	- exercitation ullamco laboris nisi ut 
2. aliquip ex ea commodo consequat.

- test
	1. test
		- test

## Task lists
There are lots of variations for these. We will try to list some common ones here. 

- **The basics**
	- [ ] incomplete
		- [ ] test
			- [ ] test
				- [ ] test
					- [ ] test
						- [ ] test
							- [ ] test
								- [ ] test
									- [ ] 
	- [x] `x` complete / done
	- [X] `X` complete / done (Failed in Sanctum)
- **Completion / GTD / bullet journal flavors**
	- [-] `-` cancelled 
	- [>] `>` deferred
	- [/] `/` for in progress, or half-done
	- [!] `!` for Important
	- [?] `?` for question

- [ ] test
- [ ] test
- [ ] test
- [ ] test
- [ ] test
- [ ] test
- [ ] test

- test
	- test
		- test
			- [ ] test
			- [ ] 

### Examples

Not all themes support all of these variations. Here are a few examples. These are also snapshots, see the themes for the latest. ;)

#### Ebullientworks

![[ebullientworks-common-tasks.png|400]]

##### Additional types

![[ebullientworks-custom-tasks.png|200]]

###### Sample text

- [R] `R` for review

#### ITS Theme

![[ITS-common-tasks.png|600]]

##### Additional types

![[ITS-custom-tasks.png]]

###### Sample text: 

- [+] `+` Inbox / task that should be processed later
- [b] `b` bookmark 
- [B] `B` brainstorm
- [D] `D` deferred or scheduled
- [ ] `I` for Info
- [i] `i` for idea
- [N] `N` for note
- [Q] `Q` for quote
- [R] `R` for research
- [W] `W` for win / success / reward 
- **Pro/Con list**
	- [P] `P` for pro
	- [C] `C` for con


#### Sanctum

![[sanctum-common-tasks.png|500]]

##### Additional types

Sanctum has some adjusted meanings (note differences to ITS)

![[sanctum-custom-tasks.png|300]]

###### Sample text: 

- [a] `a` for alarm
- [b] `b` for bookmark
- [B] `B` for bug
- [n] `n` for note
- [I] `I` for idea
- [i] `i` for information
- [l] `l` for Location
- [<] `<` scheduled
- [>] `>` for deferred / rescheduled
- **Success and failure**
	- [1] `1` for Success
	- [x] `W` for Win / Success / Reward
	- [X] `X` for failure 
- **Money**
	- [s] `s` for savings
	- [S] `S` an alternative for savings
- **Pro/Con list**
	- [P] `p` for pro
	- [c] `c` for con
- **Emoji**
	- [⭐] ⭐ for a starred item
	- [❤] ❤ for a heart item


#### Spectrum

![[spectrum-common-tasks.png|500]]