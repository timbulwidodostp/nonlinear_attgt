# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Nonlinear Staggered Difference-in-Differences (DiD) Group-Time ATT Estimation Use nonlinear_attgt (NonlinearDiD) With (In) R Software
install.packages("NonlinearDiD")

library("NonlinearDiD")
# Estimation Nonlinear Staggered Difference-in-Differences (DiD) Group-Time ATT Estimation Use nonlinear_attgt (NonlinearDiD) With (In) R Software
nonlinear_attgt = read.csv("https://raw.githubusercontent.com/timbulwidodostp/nonlinear_attgt/main/nonlinear_attgt/nonlinear_attgt.csv",sep = ";")
nonlinear_attgt <- nonlinear_attgt(data = nonlinear_attgt, yname = "y", tname = "period", idname = "id", gname = "g", outcome_model = "logit")
summary(nonlinear_attgt)
# Nonlinear Staggered Difference-in-Differences (DiD) Group-Time ATT Estimation Use nonlinear_attgt (NonlinearDiD) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished