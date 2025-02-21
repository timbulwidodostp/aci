# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Absolute concentration index (ACI) Use aci (healthequal) With (In) R Software
install.packages("healthequal")
library("healthequal")
aci = read.csv("https://raw.githubusercontent.com/timbulwidodostp/aci/main/aci/aci.csv",sep = ";")
# Estimation Absolute concentration index (ACI) Use aci (healthequal) With (In) R Software
aci <- with(aci, aci(est = sba, subgroup_order = subgroup_order, weight = weight, psu = psu, strata = strata))
aci
summary(aci)
# Absolute concentration index (ACI) Use aci (healthequal) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished