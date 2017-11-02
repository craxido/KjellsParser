all:
	happy -gca ParMain.y
	alex -g LexMain.x
	ghc --make TestMain.hs -o TestMain

clean:
	-rm -f *.log *.aux *.hi *.o *.dvi

distclean: clean
	-rm -f DocMain.* LexMain.* ParMain.* LayoutMain.* SkelMain.* PrintMain.* TestMain.* AbsMain.* TestMain ErrM.* SharedString.* ComposOp.* main.dtd XMLMain.* Makefile*
	

