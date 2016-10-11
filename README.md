# SintillaNetPrinting
Add print functionallity to ScintillaNet 3.x https://github.com/jacobslusser

To Use it:

ScintillaNetPrinting.Printing printer = new ScintillaNetPrinting.Printing(Scintilla);
printer.PageSettings = new ScintillaPrinting.PageSettings() 
{ 
    ColorMode = ScintillaNePrinting.PageSettings.PrintColorMode.BlackOnWhite 
};

printer.Print();

or

printer.PrintPreview();

This is a copy and adaptation of original printing functionallity of ScintillaNet 2.6 version .
