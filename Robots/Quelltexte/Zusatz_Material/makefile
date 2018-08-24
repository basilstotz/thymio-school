PDFS = Titelblatt.pdf Einige_Roboter.pdf Welches_Verhalten.pdf Auf_der_Strasse.pdf Thymio_im_Duo.pdf Verkleide_Thymio.pdf

all: Zusatz_Material.pdf

Zusatz_Material.pdf: $(PDFS)
	pdftk $(PDFS) output Zusatz_Material.pdf 

%.pdf: %.odt
	unoconv -f pdf $<

