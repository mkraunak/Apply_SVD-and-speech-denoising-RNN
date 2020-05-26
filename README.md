# Apply_SVD-and-speech-denoising-RNN

Singular  Value  Decomposition  (SVD)  can  compress  the  weight  matrices  (Module6).   You  have  6  different  weight  matrices  in  your  baseline  network,  i.e.W(1)∈R784×1024,W(2)∈R1024×1024,···,W(5)∈R1024×1024,W(6)∈R1024×10.   Run  SVD  on  each  of  them,  except  forW(6)which is too small already, to approximate the weight matrices:W(l)≈̂W(l)=U(l)S(l)V(l)>(1

Problem 2: Speech Denoising Using RNN   Audio signals natually contain some temporal structure to make use of for the prediction job.  Speechdenoising  is  a  good  example.   In  this  problem,  we’ll  come  up  with  a  reasonably  complicated  RNNimplementation for the speech denoising job.
