# THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS

![LOCAL STORAGE FOR WEB APPLICATIONS](https://love2dev.com/img/dm_tapeuqaeiw77-1200x630.jpg)

## A BRIEF HISTORY OF LOCAL STORAGE HACKS BEFORE HTML5

Internet Explorer's userData allows web pages to store up to 64 KB of data per domain. Flash gives each domain 100 KB of storage "for free," but IE prompts the user for each order of magnitude increase in storage. Dojo Toolkit, a browser-to-end-all-browser-wars toolkit, lets you access unlimited storage. All of these solutions are either specific to a single browser or reliant on a third-party plugin. Despite heroic efforts to paper over the differences, they all expose radically different interfaces and storage limitations. HTML5 aims to provide a standardized API, implemented natively and consistently in multiple browsers.

## INTRODUCING HTML5 STORAGE

What I will refer to as “HTML5 Storage” is a specification named Web Storage, which was at one time part of the HTML5 specification proper, but was split out into its own specification for uninteresting political reasons. Certain browser vendors also refer to it as “Local Storage” or “DOM Storage.” The naming situation is made even more complicated by some related, similarly-named, emerging standards that I’ll discuss later in this chapter.

So what is HTML5 Storage? Simply put, it’s a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the web site, close your browser tab, exit your browser, or what have you. Unlike cookies, this data is never transmitted to the remote web server (unless you go out of your way to send it manually). Unlike all previous attempts at providing persistent local storage, it is implemented natively in web browsers, so it is available even when third-party browser plugins are not.

Which browsers? Well, the latest version of pretty much every browser supports HTML5 Storage… even Internet Explorer!

### HTML5 STORAGE SUPPORT

| Browsers | Version |
| ------------ | ------------- |
| Internet Explorer | 8.0+ |
| Safari | 4.0+ |
| Chrome | 4.0+ |

## USING HTML5 STORAGE

HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. However, the data is actually stored as a string. If you are storing and retrieving anything other than strings, you will need to use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype.

 interface Storage {

  getter any getItem(in DOMString key);

  setter creator void setItem(in DOMString key, in any data);

 };

Calling setItem() with a named key that already exists will silently overwrite the previous value. Calling getItem() with a non-existent key will return null rather than throw an exception.

## HTML5 STORAGE IN ACTION

Let’s see HTML5 Storage in action. Recall the Halma game we constructed in the canvas chapter. There’s a small problem with the game: if you close the browser window mid-game, you’ll lose your progress. But with HTML5 Storage, we can save the progress locally, within the browser itself. Here is a live demonstration. Make a few moves, then close the browser tab, then re-open it. If your browser supports HTML5 Storage, the demonstration page should magically remember your exact position within the game, including the number of moves you’ve made, the position of each of the pieces on the board, and even whether a particular piece is selected.

### For more info [Click here](http://diveinto.html5doctor.com/storage.html)