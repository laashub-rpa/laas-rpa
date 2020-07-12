# Component

component by: Designer + Agent + Server + Distribution

temp ignore the Server + Distribution, just as a development toolkit for us

now it component by: Finder + Picker + Processor + Tester + Debugger + Runner

Finder: through the finder to get useful-way

Picker: through the picker to get target element-info

Processor: through the processor to choreography the details business process

Tester: through the tester to get the difference of  the large number of test

Debugger: through the debugger to implement continue development

Runner: host the target device, run designer's command, display the log of step, send-back info to designer or server

# Picker: Core-Data

element-data

business-data

## Element-Data

### 4 kind of:

the data of find element

the data of find element's event

the data of operate element

the data of element's self-data and level-data(parent、friends、children)

#### the data of find element

##### browser

selenium

gen: xpath

2 level element: original element、wrap element

##### software

pywinauto(base handle)

pyautogui(base keyboard + mouse + ocr)

gen: xpath

2 level element: original element、offset element

#### the data of find element's event

#### the data of operate element

#### the data of element's self-data and level-data(parent、friends、children)

### 5 level of:

element

function

module

system

scenes



in those 5 level, have lost of number, need the package、extends、standard to group use



through the box to operate target level

#### box:

define target

compatible the exception event

manage status

isolation, independent



proxy target level for find、operate、get

# Processor

## basic-way

basic compute function

step:

​	call

​	loop(loop_condition、loop_index、scope_data)

​	break:

​		break、continue

fork:

​	if-else

class、function:

​	order: preview、next、doing

​	box: input、output

​	life-cycle: load、create、running、destroy

module:

​	extract sub-class/sub-function and to call it

view:

​	quick switch code-view

​	display flow graph

​	display component graph

​	display status-change graph

## process-data

as much as possible to precipitate data at every step



each step has its own local data block



in order to cut into every step point at any time, we need to precipitate data and snapshot software running memory data(snapshot is a think idea at this moment for me)



use the way of main-line-child-line, isolate steps as much as possible

the actual main-line need to manage the actual child-line, manage status, recover, timed detection...













