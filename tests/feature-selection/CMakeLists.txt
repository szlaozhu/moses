ADD_CXXTEST(feature_selectionUTest)
TARGET_LINK_LIBRARIES(feature_selectionUTest
	feature_selection
	moses
	${COGUTIL_LIBRARY}
)
