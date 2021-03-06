# 105 JavaScript Event Handlers

This list is taken from [OWASP XSS Filter Evasion Cheat Sheet](https://www.owasp.org/index.php/XSS_Filter_Evasion_Cheat_Sheet)

<br><b>FSCommand</b> (attacker can use this when executed from within an embedded Flash object)
<br><b>onAbort</b> (when user aborts the loading of an image)
<br><b>onActivate</b> (when object is set as the active element)
<br><b>onAfterPrint</b> (activates after user prints or previews print job)
<br><b>onAfterUpdate</b> (activates on data object after updating data in the source object)
<br><b>onBeforeActivate</b> (fires before the object is set as the active element)
<br><b>onBeforeCopy</b> (attacker executes the attack string right before a selection is copied to the clipboard - attackers can do this with the execCommand("Copy") function)
<br><b>onBeforeCut</b> (attacker executes the attack string right before a selection is cut)
<br><b>onBeforeDeactivate</b> (fires right after the activeElement is changed from the current object)
<br><b>onBeforeEditFocus</b> (Fires before an object contained in an editable element enters a UI-activated state or when an editable container object is control selected)
<br><b>onBeforePaste</b> (user needs to be tricked into pasting or be forced into it using the execCommand("Paste") function)
<br><b>onBeforePrint</b> (user would need to be tricked into printing or attacker could use the print</b> or execCommand("Print") function).
<br><b>onBeforeUnload</b> (user would need to be tricked into closing the browser - attacker cannot unload windows unless it was spawned from the parent)
<br><b>onBeforeUpdate</b> (activates on data object before updating data in the source object)
<br><b>onBegin</b> (the onbegin event fires immediately when the element's timeline begins)
<br><b>onBlur</b> (in the case where another popup is loaded and window looses focus)
<br><b>onBounce</b> (fires when the behavior property of the marquee object is set to "alternate" and the contents of the marquee reach one side of the window)
<br><b>onCellChange</b> (fires when data changes in the data provider)
<br><b>onChange</b> (select, text, or TEXTAREA field loses focus and its value has been modified)
<br><b>onClick</b> (someone clicks on a form)
<br><b>onContextMenu</b> (user would need to right click on attack area)
<br><b>onControlSelect</b> (fires when the user is about to make a control selection of the object)
<br><b>onCopy</b> (user needs to copy something or it can be exploited using the execCommand("Copy") command)
<br><b>onCut</b> (user needs to copy something or it can be exploited using the execCommand("Cut") command)
<br><b>onDataAvailable</b> (user would need to change data in an element, or attacker could perform the same function)
<br><b>onDataSetChanged</b> (fires when the data set exposed by a data source object changes)
<br><b>onDataSetComplete</b> (fires to indicate that all data is available from the data source object)
<br><b>onDblClick</b> (user double-clicks a form element or a link)
<br><b>onDeactivate</b> (fires when the activeElement is changed from the current object to another object in the parent document)
<br><b>onDrag</b> (requires that the user drags an object)
<br><b>onDragEnd</b> (requires that the user drags an object)
<br><b>onDragLeave</b> (requires that the user drags an object off a valid location)
<br><b>onDragEnter</b> (requires that the user drags an object into a valid location)
<br><b>onDragOver</b> (requires that the user drags an object into a valid location)
<br><b>onDragDrop</b> (user drops an object (e.g. file) onto the browser window)
<br><b>onDragStart</b> (occurs when user starts drag operation)
<br><b>onDrop</b> (user drops an object (e.g. file) onto the browser window)
<br><b>onEnd</b> (the onEnd event fires when the timeline ends.
<br><b>onError</b> (loading of a document or image causes an error)
<br><b>onErrorUpdate</b> (fires on a databound object when an error occurs while updating the associated data in the data source object)
<br><b>onFilterChange</b> (fires when a visual filter completes state change)
<br><b>onFinish</b> (attacker can create the exploit when marquee is finished looping)
<br><b>onFocus</b> (attacker executes the attack string when the window gets focus)
<br><b>onFocusIn</b> (attacker executes the attack string when window gets focus)
<br><b>onFocusOut</b> (attacker executes the attack string when window looses focus)
<br><b>onHashChange</b> (fires when the fragment identifier part of the document's current address changed)
<br><b>onHelp</b> (attacker executes the attack string when users hits F1 while the window is in focus)
<br><b>onInput</b> (the text content of an element is changed through the user interface)
<br><b>onKeyDown</b> (user depresses a key)
<br><b>onKeyPress</b> (user presses or holds down a key)
<br><b>onKeyUp</b> (user releases a key)
<br><b>onLayoutComplete</b> (user would have to print or print preview)
<br><b>onLoad</b> (attacker executes the attack string after the window loads)
<br><b>onLoseCapture</b> (can be exploited by the releaseCapture</b> method)
<br><b>onMediaComplete</b> (When a streaming media file is used, this event could fire before the file starts playing)
<br><b>onMediaError</b> (User opens a page in the browser that contains a media file, and the event fires when there is a problem)
<br><b>onMessage</b> (fire when the document received a message)
<br><b>onMouseDown</b> (the attacker would need to get the user to click on an image)
<br><b>onMouseEnter</b> (cursor moves over an object or area)
<br><b>onMouseLeave</b> (the attacker would need to get the user to mouse over an image or table and then off again)
<br><b>onMouseMove</b> (the attacker would need to get the user to mouse over an image or table)
<br><b>onMouseOut</b> (the attacker would need to get the user to mouse over an image or table and then off again)
<br><b>onMouseOver</b> (cursor moves over an object or area)
<br><b>onMouseUp</b> (the attacker would need to get the user to click on an image)
<br><b>onMouseWheel</b> (the attacker would need to get the user to use their mouse wheel)
<br><b>onMove</b> (user or attacker would move the page)
<br><b>onMoveEnd</b> (user or attacker would move the page)
<br><b>onMoveStart</b> (user or attacker would move the page)
<br><b>onOffline</b> (occurs if the browser is working in online mode and it starts to work offline)
<br><b>onOnline</b> (occurs if the browser is working in offline mode and it starts to work online)
<br><b>onOutOfSync</b> (interrupt the element's ability to play its media as defined by the timeline)
<br><b>onPaste</b> (user would need to paste or attacker could use the execCommand("Paste") function)
<br><b>onPause</b> (the onpause event fires on every element that is active when the timeline pauses, including the body element)
<br><b>onPopState</b> (fires when user navigated the session history)
<br><b>onProgress</b> (attacker would use this as a flash movie was loading)
<br><b>onPropertyChange</b> (user or attacker would need to change an element property)
<br><b>onReadyStateChange</b> (user or attacker would need to change an element property)
<br><b>onRedo</b> (user went forward in undo transaction history)
<br><b>onRepeat</b> (the event fires once for each repetition of the timeline, excluding the first full cycle)
<br><b>onReset</b> (user or attacker resets a form)
<br><b>onResize</b> (user would resize the window; attacker could auto initialize with something like: <SCRIPT>self.resizeTo(500,400);</SCRIPT>)
<br><b>onResizeEnd</b> (user would resize the window; attacker could auto initialize with something like: <SCRIPT>self.resizeTo(500,400);</SCRIPT>)
<br><b>onResizeStart</b> (user would resize the window; attacker could auto initialize with something like: <SCRIPT>self.resizeTo(500,400);</SCRIPT>)
<br><b>onResume</b> (the onresume event fires on every element that becomes active when the timeline resumes, including the body element)
<br><b>onReverse</b> (if the element has a repeatCount greater than one, this event fires every time the timeline begins to play backward)
<br><b>onRowsEnter</b> (user or attacker would need to change a row in a data source)
<br><b>onRowExit</b> (user or attacker would need to change a row in a data source)
<br><b>onRowDelete</b> (user or attacker would need to delete a row in a data source)
<br><b>onRowInserted</b> (user or attacker would need to insert a row in a data source)
<br><b>onScroll</b> (user would need to scroll, or attacker could use the scrollBy</b> function)
<br><b>onSeek</b> (the onreverse event fires when the timeline is set to play in any direction other than forward)
<br><b>onSelect</b> (user needs to select some text - attacker could auto initialize with something like: window.document.execCommand("SelectAll");)
<br><b>onSelectionChange</b> (user needs to select some text - attacker could auto initialize with something like: window.document.execCommand("SelectAll");)
<br><b>onSelectStart</b> (user needs to select some text - attacker could auto initialize with something like: window.document.execCommand("SelectAll");)
<br><b>onStart</b> (fires at the beginning of each marquee loop)
<br><b>onStop</b> (user would need to press the stop button or leave the webpage)
<br><b>onStorage</b> (storage area changed)
<br><b>onSyncRestored</b> (user interrupts the element's ability to play its media as defined by the timeline to fire)
<br><b>onSubmit</b> (requires attacker or user submits a form)
<br><b>onTimeError</b> (user or attacker sets a time property, such as dur, to an invalid value)
<br><b>onTrackChange</b> (user or attacker changes track in a playList)
<br><b>onUndo</b> (user went backward in undo transaction history)
<br><b>onUnload</b> (as the user clicks any link or presses the back button or attacker forces a click)
<br><b>onURLFlip</b> (this event fires when an Advanced Streaming Format (ASF) file, played by a HTML+TIME (Timed Interactive Multimedia Extensions) media tag, processes script commands embedded in the ASF file)
<br><b>seekSegmentTime</b> (this is a method that locates the specified point on the element's segment time line and begins playing from that point. The segment consists of one repetition of the time line including reverse play using the AUTOREVERSE attribute.)
