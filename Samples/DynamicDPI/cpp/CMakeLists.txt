exe()
target_compile_definitions(${this_target} PUBLIC
	UNICODE
	_UNICODE
	)
target_link_options(${this_target} PUBLIC
/SUBSYSTEM:Windows	)
