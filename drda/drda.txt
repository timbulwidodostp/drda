# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Dose-response data analysis Use drda With (In) R Software
install.packages("drda")
library("drda")
drda = read.csv("https://raw.githubusercontent.com/timbulwidodostp/drda/main/drda/drda.csv",sep = ";")
# Estimation Dose-response data analysis Use drda With (In) R Software
drda <- drda(response ~ log_dose, data = drda)
summary(drda)
# Dose-response data analysis Use drda With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished