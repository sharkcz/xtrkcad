
# $Header: /home/dmarkle/xtrkcad-fork-cvs/xtrkcad/app/lib/CMakeLists.txt,v 1.6 2008-03-27 18:17:16 m_fischer Exp $
#

PROJECT(lib)

ADD_SUBDIRECTORY(demos)
ADD_SUBDIRECTORY(examples)
ADD_SUBDIRECTORY(params)

INSTALL(FILES 
	COPYING
	Readme.txt
	logo.bmp
	xtrkcad.bug
	xtrkcad.enh
	xtrkcad.fix
	xtrkcad.xtq
	DESTINATION ${XTRKCAD_SHARE_INSTALL_DIR}
	)
