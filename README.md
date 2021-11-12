# DominoEncryptDatabase

# read enctyption level
Call EncryptGet()

# remove encryption level
Call EncryptUpdate(ENCRYPT_OPTION_REMOVE, ENCRYPT_STRENGTH_NONE)

# update encryption level
Call EncryptUpdate(ENCRYPT_OPTION_MODIFY, ENCRYPT_STRENGTH_STRONG)
