---
layout: page
title: CV
permalink: /CV
---

<!--- For buttons -->
<head>
<script>
function myFunction(id) {
	var x = document.getElementById(id);

	var ids = ["abs1", "media1", "abs2", "media2", "abs3", "about1", "about2"];

	for(var i = 0; i < ids.length; i++) {
		var item = ids[i];
		if (item != id) {
			document.getElementById(item).style.display = "none";
		} else {
			if (x.style.display === "none") {
				x.style.display = "block";
			} else {
				x.style.display = "none";
			}
		}
	}


}
</script>
</head>


**Education**  
Princeton '16 (A.B., Applied Mathematics/Economics)

**Experience**  
Morgan Stanley (Previously an investment analyst in NYC, 1585 Broadway)

**Publications**  
"[On the distribution of DNA translocation times in solid-state nanopores: an analysis using Schrödinger's first-passage-time theory](https://iopscience.iop.org/article/10.1088/0953-8984/25/37/375102/meta)," August 2013. Published in the *Journal of Condensed Matter Physics*.  
"[Composite Gold-Silver Alloy Nanoparticles for GFP Interactions](https://pdfs.semanticscholar.org/4900/eb3fbe32df15c0c12232e6a64c0060b989e5.pdf)," 2011. *Submitted*.

**Honors**  
U.S. Presidential Scholar  
National Merit Scholar  


<details><summary>CLICK ME</summary>
<p>

#### yes, even hidden code blocks!

```python
print("hello world!")
```

</p>
</details>



<details>
<summary><span style="color: grey;">Additional Honors</span></summary>
<p>
Intel Science Talent Search (2012, Semifinalist)
<br>
Intel International Science & Engineering Fair (2011, Finalist and Special Award Winner)
<br>
Siemens Competition (2011, Finalist)
<br>
JSHS National Competition (2011, 3rd Place at National Finals, San Diego)
<br>
Harvard Book Award
<br>
Valedictorian, East Greenwich High School
<br>
Rhode Island Science Fair (2011, Overall Winner - Senior Division Champion)
</p>
</details>



<button class="button" onclick="myFunction()">
Additional Honors
</button>

							<div class="popup"  style="display:none;">
								Intel Science Talent Search (2012, Semifinalist)
								<br>
								Intel International Science & Engineering Fair (2011, Finalist and Special Award Winner)
								<br>
								Siemens Competition (2011, Finalist)
								<br>
								JSHS National Competition (2011, 3rd Place at National Finals, San Diego)
								<br>
								Harvard Book Award
								<br>
								Valedictorian, East Greenwich High School
								<br>
								Rhode Island Science Fair (2011, Overall Winner - Senior Division Champion)
							</div>
