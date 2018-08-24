PDFS = Titelblatt.pdf 06.1_Zeichne_einen_Roboter.pdf 07.1_Einige_Roboter.pdf 08.1_Einige_Roboter.pdf 09.12_Thymio_einschalten.pdf 09.1_Thymio_einschalten.pdf 10.1_Thymios_Farben.pdf 11.1_Welches_Verhalten.pdf 13.12_Baue_einen_Parcours.pdf 13.1_Baue_einen_Parcours.pdf 14.1_Thymio_zeichnet.pdf 14.2_Thymio_zeichnet.pdf 15.1_Die_Tunnel.pdf 15.11_Die_Tunnel.pdf 16.1_Auf_der_Strasse.pdf 17.1_Thymio_Slalom_1.pdf 17.1_Thymio_Slalom_2.pdf 18.1_Thymio_im_Duo.pdf 18.1_Thymio_im_Trio.pdf 20.1_Verkleide_Thymio.pdf

NICHT = 19.1_Uebernimm_das_Kommando_1.pdf 19.1_Uebernimm_das_Kommando_2.pdf 19.1_Uebernimm_das_Kommando_3.pdf  

all: Arbeitsblaetter.pdf

Arbeitsblaetter.pdf: $(PDFS)
	pdftk $(PDFS) output Arbeitsblaetter.pdf

%.pdf: %.odt
	unoconv -f pdf $<

%.pdf: %.odg
	unoconv -f pdf $<


