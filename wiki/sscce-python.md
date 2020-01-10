# The SSCCE - Python (DRAFT - Needs work)

## Short, Self Contained, Correct (Compilable), Example

If you are having a problem with some code and seeking help, preparing a Short, Self Contained, Correct Example (<abbr title="Short, self contained, correct example">SSCCE</abbr>) is very useful. But what is an SSCCE?

It is all in the name, really. Take a look at each part. The version prepared for others to see should be:

*   <a>Short</a> (Small) - Minimise bandwidth for the example, do not bore the audience.
*   <a>Self Contained</a> - Ensure everything is included, ready to go.
*   <a>Correct</a> - Copy, paste, (compile,) see is the aim.
*   <a>Example</a> - Displays the problem we are trying to solve.

## <a id="short" rel="nofollow">Short</a>

This depends on the group or forum. For a public forum, most readers will stop reading by 100 lines of code, and start complaining at 250-300 lines of code.

### <a id="trim" rel="nofollow">Tricks for Trimming</a>

If the GUI has 40 buttons not related to the problem, remove them. If they _are_ related to the problem (you remove them and the problem disappears) put one or two back in, if the problem reappears, include _only_ those one or two buttons.

The list, tuple or dictionary that is causing a problem may have a hundred entries, but again, if the problem can be seen with two or three entries, trim the example to that alone.

If trimming a very large amount if code for others to see, you might trim out a part of it early on that you think is not related to the problem, yet the problem is fixed.

### <a id="solution" rel="nofollow">Problem Solved?</a>

By identifying more clearly where the problem occurs, you have just made an important step toward solving it. The process that highlights where a problem _originates_ can, in itself, help to solve it. You might look more closely at the part cut out, and in doing so, spot the problem.

Even if you cannot see why the problem occurs, you have still made an important step: identifying (at least part) of the code involved.

If the code being trimmed is now a concise example of the problem, it is ready to present to others, if not, put the problem code back in and continue trimming other areas of the code until it is.

## <a id="selfcon" rel="nofollow">Self Contained</a>

It is important to ensure that the code given to others can be 'copied, pasted, compiled, run' so that they can help quickly and with a minimum of fuss.

This means that after the code has been copied, pasted and compiled by those helping, they can run it and _see_ the results for themselves. It is the <a>example</a> of the problem.

You are much more likely to receive help if you do this.

### <a id="selfcontained" rel="nofollow">How to make an example self contained.</a>

If the code performs I/O to files, replace the file I/O with dummy data structures in problems that are unrelated to input/output.

If the problem _is_ the input and textual input can be used, prepare a short example that can be copied for the actual file data.

Should the problem happen only under load, insert code to simulate that load. If a layout problem only occurs under particular circumstances, _force_ those things to happen, if it is practical to do so.

Obviously there are things that cannot be included in an example that is posted to a forum, 'a database' etcetera, but many times you just need a bit of lateral thinking to come up with a way to replace something you thought was 'vital' to demonstrate a problem.

One example of lateral thinking is 'images'. Images related to code problems might seem difficult to replace. But one trick is to link to an image available on the web, one that displays the same problem. Try to make any web based images 'small' in bytes - if at all possible.

## <a id="co" rel="nofollow">Correct</a>

> If my example was correct, _what would I be doing here?_

(Laughs) No, that is not what 'correct' means in this context. In this document, correct (or compilable, which particularly relates to computer source code) means ensuring that the example fits the accepted standards and protocols.

To achieve that, it is necessary to:

*   <a id="linewidth" rel="nofollow">Line width</a> Keep the width of the lines in the example to under 62 characters wide. (but please do **not** remove all line indents!) Newsreaders typically force a line wrap at around 72 characters (and it pays to 'play it safe by using less than that). _Sometimes_ line wrap does not cause any problem with the example, but it _usually_ does, and means the lines need to be rejoined or reconstructed, before they work as intended.  
    Most code/source editors will show a column width along the top of the editing area.
*   <a id="nameconvention" rel="nofollow">Use the naming convention</a>, if one exists. Most of the people willing to help will be using hints from the formatting of upper and lower case letters, as well as their descriptive names, to skim the code in the hope of spotting the problem quickly. If following the conventions the audience is used to, it helps them to do that.
*   <a id="valid" rel="nofollow">Ensure the example is _correct_.</a> Either the example compiles cleanly, or causes the exact error message about which needs solving.

Further tips:

*   Move all resources (CSS/JS/Java source, images etc.) to the same directory, so they are easier to administer, and easier to find.
*   Remove package statements from Java code.
*   Demote public Java classes to default. If the language specifies only a single public class per source code file, demote all the other classes to default. This allows the example to be compiled without being split into separate files.
*   Validate the example, where a validator is available.
    *   <abbr title="HyperText MarkUp Language">HTML</abbr> [validator](http://validator.w3.org/)
    *   <abbr title="Cascading Style Sheets">CSS</abbr> [validator](http://jigsaw.w3.org/css-validator/)

## <a id="eg" rel="nofollow">Example</a>

_Make sure the posted code, displays the problem!_

You have worked on the example for hours, perhaps days. It feels like forever. Now is a good time to take a breather, step back, stretch, perhaps go for a refreshing walk.

_Refresh the computer as well._ Reboot it if necessary.

Now open the pages, or program, where the problem occurs. Is it still there?

Perhaps 99% of the time it is (maybe less if using a less reliable operating system).

Now, if the problem is still there, post the example.

### <a id="extra" rel="nofollow">Example - Extra Points</a>

We wish we had a dollar for every person who asked for help about a web page or the stylesheet for one, some JavaScript code, or a Java Applet - and did not provide a link. We would not need to supply and maintain this document, instead we would be sunning ourselves on a beach in an exotic location, drinking still more exotic cocktails.

Why do people miss such an opportunity? Very few things are as tempting as a link to the problem. To a seasoned forum helper, it is almost as tempting as a small bottle with the vague message 'drink me', ..or an exotic cocktail.

Having a group of people look at the problem helps to identify and solve the problem at hand, as well as _compatibility problems_ (which might be the cause of the problem all along).

### <a id="standards" rel="nofollow">Standards on the Internet</a>

Therein lies another 'gotcha' when dealing with most things related to the internet. The internet, as well as most things associated with it, is just a little bit wild. For every standard there are two alternates. For every rule there are at least three exceptions to the rule.

To start with, browsers do not work the same. We are not just referring to differences between IE and Netscape, or old and new browsers, but 'Internet Explorer 5' for the Macintosh, for example, is a (significantly) different browser from 'Internet Explorer 5' for Windows.

People asking for help on web-design groups are often surprised to hear that the problem they are experiencing with a web page does not even show for others using different browsers.

### <a id="devapplet" rel="nofollow">Java Applets</a>

Another level of complexity, and more chance of problems, is introduced when Applets are in the web page. How the random clutch of browsers mentioned above will react to (often poorly formed) html and styles, with Applets thrown into the mix as well, is another matter again. Here is just one example.

For a long time MicroSoft was shipping the Internet Explorer browser with an _older version of Java_ (a version 1.1 <abbr title="Java Virtual Machine, the emulator in which Java Applets run.">JVM</abbr>). After some events happened, MS put the _latest Java_ engines into its browsers. Soon after that, they began to supply the IE with _no JVM at all_.

Given the possible complications with Applets, it is fortunate that they are so easy to check when on they are on the internet. A few clicks and someone on the other side of the planet can be reading the output from the Java console of _their own browser_ or, sometimes, see the Applet working perfectly.

If the Applet that fails for you works in someone else's browser, it helps to quickly narrow the scope of the problem to the html, the applet tag, or the JVM installed in the browser (or complete lack of one).

## <a id="bother" rel="nofollow">Why bother?</a>

A very good question. Why go to all this effort?

Perhaps someone can understand the problem you describe from the description you give. Maybe it is one of those things that a thousand people before have stumbled on.

If you have already checked the FAQ, Googled the forum, read the ..flaming manual it is unlikely that an answer will pop up that easily. You _have_ done those things, haven't you?

If wasting the time and bandwidth of the other members of a public forum, you risk members of the group delivering short sharp rebukes.

The people who contribute to the groups give a wide range of advice. Sometimes the advice works, sometimes it does not, but either way, the advice is free.

Contributors do so for a variety of reasons, including the nice feeling they get when they can pass on a piece of knowledge relating to their chosen field to someone who is learning.

Unfortunately, if someone asks to be spoon fed information that is contained in a basic tutorial, it is a strong indication that the questioner does not so much want to learn as get others to do work they should be doing themselves.

If there is a piece of code and you wish to have it written, finished or fixed by others, there are plenty of avenues to achieve that. For a modest amount of money, you can get most IT work completed (or done) through a number of internet based outsourcing companies. That is what such companies specialize in.

Free forums are for people to learn.

Having said that:

Let us assume you are indeed genuine in your learning, you have a huge, complex system with an occasional, unpredictable bug, and you _have_ searched the FAQ & Group, studied the manual or documentation and not produced an answer.

Feel free to describe the problem to the group; perhaps it is a basic misunderstanding on your part that can easily be cleared up.

**<a id="compulsory" rel="nofollow">We</a><a id="every" rel="nofollow"></a> are not proposing that every single problem needs a SSCCE in order to be solved. We are also not suggesting an example is, or should be, compulsory.**

It will, however, make people much _more likely to help_, and will therefore _increase the chance of finding a solution_.
