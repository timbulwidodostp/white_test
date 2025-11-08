# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# This function performs a White's Test for heteroskedasticity (White, H. (1980)) Use white_test (whitestrap) With (In) R Software
install.packages("whitestrap")
library("whitestrap")
white_test = read.csv("https://raw.githubusercontent.com/timbulwidodostp/white_test/main/white_test/white_test.csv",sep = ";")
# Estimation This function performs a White's Test for heteroskedasticity (White, H. (1980)) Use white_test (whitestrap) With (In) R Software
white_test <- lm(Dependen ~ Independen_1 + Independen_2 + Independen_3, data = white_test)
white_test_ <- white_test(white_test)
white_test_boot <- white_test_boot(white_test)
white_test_
white_test_boot
# This function performs a White's Test for heteroskedasticity (White, H. (1980)) Use white_test (whitestrap) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished