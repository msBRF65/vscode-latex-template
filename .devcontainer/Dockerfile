# Copyright (c) 2016 Kaito Udagawa
# Copyright (c) 2016-2020 3846masa
# Released under the MIT license
# https://opensource.org/licenses/MIT

FROM paperist/texlive-ja:latest

RUN apt-get update && apt-get install -y git
RUN tlmgr install newtx

WORKDIR /workdir
COPY .latexmkrc /root

