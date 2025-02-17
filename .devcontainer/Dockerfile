FROM pandoc/latex:latest-ubuntu

RUN apt update \
    && apt -y install git

RUN tlmgr install accsupp changepage cmap dashrule dirtytalk enumitem everyshi extsizes fontawesome5 fontaxes iftex koma-script lato paracol pdfx ragged2e simpleicons tcolorbox tikzfill xkeyval xmpincl

ENTRYPOINT ["/usr/bin/bash"]
