DEFINES+=PROJECT_CONF_H=\"project-conf.h\"

HAVE_BANKING=1

CONTIKI_PROJECT = MainSource

all: $(CONTIKI_PROJECT) 

CONTIKI = ../../..
CONTIKI_WITH_IPV6 = 1
# needed for rimestats
CONTIKI_WITH_RIME = 1
include $(CONTIKI)/Makefile.include
