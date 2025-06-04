# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Intrinsic Parameters Estimation Use intrinsic.pars (multgee) With (In) R Software
install.packages("multgee")
library("multgee")
intrinsic.pars = read.csv("https://raw.githubusercontent.com/timbulwidodostp/intrinsic.pars/main/intrinsic.pars/intrinsic.pars.csv",sep = ";")
# Estimation Intrinsic Parameters Estimation Use intrinsic.pars (multgee) With (In) R Software
intrinsic_pars_1 <- intrinsic.pars(y, intrinsic.pars, id, time, rscale = "ordinal")
intrinsic_pars_2 <- intrinsic.pars(y, intrinsic.pars, id, time, rscale = "nominal")
intrinsic_pars_1
intrinsic_pars_2
# Intrinsic Parameters Estimation Use intrinsic.pars (multgee) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished