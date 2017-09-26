## Version 0.1.7:

    2004-04-30:

        - Added scientific calculator example (calc1)
        - Added support for error-handling rules
        - Added support for rule handlers to raise errors

## Version 0.1.6:

    2004-04-30:

        - Added ANSI C parser to examples

## Version 0.1.5:

    2004-04-30:

        - Added XML support - can now export and import parse trees to/from
          XML strings or xml.dom.minidom objects

## Version 0.1.4:

    2004-04-29:
    
        - Improved the layout and usability of python parser files generated
          by the bison2py utility, particularly with the '-c' option enabled

        - fixed the 'template' example, so that it actually works if used as is

        - tidied up and fleshed out the walkthrough document

## Version 0.1.3:

    2004-04-28:
    
        - java example:
        
            - replaced grammar file with an adapted version of one
              from the GNU gcj compiler source - the damn thing works now!
              
            - fixed lex script

        - core - added support for a 'debug' flag keyword argument to Parser.run(),
          which causes the bison-generated parser to haemorrhage out all manner of
          detailed debug info

        - various other fixes and tidy-ups

## Version 0.1.2:

    2004-04-25:

        - moved pure-python code from bison.pyx (now renamed to bison_.pyx),
          into a new file 'bison.py'.
          
        - patched by Eugene Oden to fix bug in processing legacy rules files
          in cases where rules contained character literals

        - added '-c' option to bison2py utility, which causes the generation
          of handler code as separate node classes instead of methods

## Version 0.1.1:

    2004-04-23:
    
        - changed call signature for user target callbacks, to a much faster and 
          more convenient form
        
        - fixed several fatal bugs
        
        - added java parser example

## Version 0.1.0:

    2004-04-23:
    
        - first release
