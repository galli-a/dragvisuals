# `dragvisuals`

Copy of the `dragvisuals.vim` plugin by Damian Conway, to allow dragging ov visual block regions

## Usage

To use create mappings to the function, for example

	vmap <expr> <LEFT> DVB_Drag('left')
	vmap <expr> <RIGHT> DVB_Drag('right')
	vmap <expr> <DOWN> DVB_Drag('down')
	vmap <expr> <UP> DVB_Drag('up')
	vmap <expr> D DVB_Duplicate()


