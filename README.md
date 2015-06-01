### sorcery-app
-------------



Sorcery is a stripped-down, bare-bones authentication library, with which you
can write your own authentication flow. It was built with a few goals in mind:

*   Less is more - less than 20 public methods to remember for the entire
    feature-set make the lib easy to 'get'.
*   No built-in or generated code - use the library's methods inside *your
    own* MVC structures, and don't fight to fix someone else's.
*   Magic yes, Voodoo no - the lib should be easy to hack for most developers.
*   Configuration over Confusion - Centralized (1 file), Simple & short
    configuration as possible, not drowning in syntactic sugar.
*   Keep MVC cleanly separated - DB is for models, sessions are for
    controllers. Models stay unaware of sessions.
