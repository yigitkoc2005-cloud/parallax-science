# How Can 4 Stickers Make AI Read STOP as 45?

**Value-first explanation (for Reddit / Quora / Dev.to / Substack):**

Your eyes read STOP. But how could stickers make one classifier see Speed Limit 45? Everyone assumes the car sees a sign. It doesn't. It sees a grid of numbers. Layer by layer, those numbers become one score per sign. Stop usually wins. But four small stickers nudge those scores. Stop slips. Speed Limit climbs. Therefore the car crosses an invisible line, a decision boundary, and the answer flips. But here's the strange part: experts still argue why this works. Some say the model is fragile, like a bridge with one weak bolt. Others say it spots real patterns we can't. Both have evidence. Therefore the machine isn't dumb. It's just reading differently. The relief: engineers can train cars against these tricks, making them harder to fool. Next time you see STOP, remember: your eyes read it. A car must decide.

**Sources:**
- Eykholt K, Evtimov I, Fernandes E, Li B, Rahmati A, Xiao C, Prakash A, Kohno T, Song D, 2018, Robust Physical-World Attacks on Deep Learning Visual Classification, CVPR 2018:1625-1634 (stickers on real signs fooled classifiers; results depend on the model and test setup)
- Szegedy C, Zaremba W, Sutskever I, Bruna J, Erhan D, Goodfellow I, Fergus R, 2014, Intriguing properties of neural networks, ICLR 2014 (arXiv:1312.6199) (first showed tiny input changes can flip a network's answer)
- Ilyas A, Santurkar S, Tsipras D, Engstrom L, Tran B, Madry A, 2019, Adversarial Examples Are Not Bugs, They Are Features, NeurIPS 32 (argues they exploit real but human-invisible patterns; this view is still debated)

**45-second visual breakdown:** https://youtube.com/shorts/W_VmzUbnNv4
**Full transcript & Q&A:** https://parallaxscience.pages.dev/shorts/sticker_turns_stop_sign/
