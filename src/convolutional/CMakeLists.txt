set(SRCFILES bit.c metric.c history_buffer.c error_buffer.c lookup.c convolutional.c encode.c decode.c)
add_library(correct-convolutional OBJECT ${SRCFILES})
