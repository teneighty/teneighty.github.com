
all: site serve

site:
	lacy *.mkd
	mv -f _output/* ..
	rmdir _output

serve:
	cd ..; python -m SimpleHTTPServer 4000

clean:
	@echo "Cleaning"
	@rm -f ../*.* 
	@rm -rf ../styles

.PHONY: all site serve clean
