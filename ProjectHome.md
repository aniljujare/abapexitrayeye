# Updates #
**9-Nov-2011** [abapexitrayeye](https://cw.sdn.sap.com/cw/groups/abapexitrayeye) project born in [SAP CodeExchange](http://scn.sap.com/community/code-exchange)

**29-Nov-2011** Check for the available releases at https://cw.sdn.sap.com/cw/releases/viewall/1212

**29-Nov-2011** Please check the [fixed issues](https://cw.sdn.sap.com/cw/issues/viewall/1212) section for solutions of little bugs

https://cw.sdn.sap.com/cw/groups/image/1212/1.png?a=89693

# Highlights #
Finally the SAP has developed the ABAP SNIF, a kind of "Exit Browser" that avoids launching dozen of transactions in the system (excluding the various checks).

I investigated thru the implementation of the SNIF program concluding that even if the idea is wonderful and the program is useful it could be enhanced to include other type of exits

And now I’m glad to share with the great SDN Community my own extended version of the SNIF that detects all types of missing exits: X-it RAY EYE.

X-it RAY Eye means ... X-Ray Eye + X-it (= Exit) =>  X-it RAY Eye

Thus the abap that I would like to share is the "son" of the SNIF program, because it uses his "architecture" with the difference that extends the search to the following types of exit:

  * Include USEREXITS
  * VOFM Form Routines
  * Exit for VALIDATIONS
  * Exit for SUBSTITUTIONS
  * SCREEN EXIT
  * MENU EXIT
  * CHANGED KEYWORDS

The ECC Version of X-it Ray Eye extends the search to the enhancement implementations:

  * SOURCE CODE Enhancements
  * FUNCTION Enhancements
  * CLASS Enhancements
  * BAdI Enhancements

Some of these items are not properly ABAP, however I've collected them in the tool.