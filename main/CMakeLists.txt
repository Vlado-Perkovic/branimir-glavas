idf_component_register(SRCS
                           "main.c"
			REQUIRES driver BME690_SensorAPI
                    INCLUDE_DIRS ".")
