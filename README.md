# AcoraCMS_10.7.1_Improper_access_control
The vulnerability arises from missing or improper server-side access control on the file_rename.asp endpoint. The application fails to verify the user's role before allowing file operations in the restricted "System Files" directory, thereby permitting low-privileged users (editors) to perform actions reserved for admin users.
