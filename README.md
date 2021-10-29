<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>B-V eq.</title>
    <script type="text/x-mathjax-config">
  MathJax.Hub.Config({tex2jax: {inlineMath: [['$','$'], ['\\(','\\)']]}});
    </script>
    <script type="text/javascript"
            src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML">
    </script>
     



</head>
<body>
<h1><font face="DFKai-SB">氧氧化還原反應</font></h1>
<pre><h2><font face="DFKai-SB">還原反應</font><font face="Segoe Script">（Reduction）</font></h2></pre>
$$The\ energy\ level\ of\ electrons\ in\ electrode\ high\ enough\ to\ transfer\ into\ vacant\ electronic\ states\ on\ species\ in\ then\ electrolyte$$
$$A+e\rightarrow A^{-}$$
<pre><h2><font face="DFKai-SB">氧化反應</font><font face="Segoe Script">（Oxidation）</font></h2></pre>
$$The\ energy\ level\ of\ electrons\ in\ electrode\ low\ enough\ to\ transfer\ from\ vacant\ electronic\ states\ on\ species\ in\ then\ electrolyte$$
$$A-e\rightarrow A^{+}$$
<pre><h2><font face="DFKai-SB">反應速率</font><font face="Segoe Script">（Reaction Rate）</font></h2></pre>

\begin{split}
& v\left ( mol/s \right ) =\frac{i}{nFA}\\
& F:Faradaic\ Constant\\
& n:Stoichiometric\ Number\\
& A:area\\
\end{split}

<h1><font face="Segoe Script">Butler-Volmer Model of Electrode Kinetics</font></h1>
<pre><h2><font face="DFKai-SB">反應速率</font></h2></pre>

\begin{split}
& A\rightleftharpoons B\\
& k:rate\ constant\\
& C:concentration\\
& v_{f}=k_{f}C_{A},v_{b}=k_{b}C_{B}\\
& v=k_{f}C_{A}-k_{b}C_{B}\\
& i=i_{f}-i_{b}=nFA\left (k_{f}C_{A}-k_{b}C_{B}  \right )
\end{split}

<pre><h2><font face="DFKai-SB">交換速率</font><font face="Segoe Script">（exchange velocity）</font></h2></pre>
\begin{split}
& at\ equilibrium:\\
& \frac{k_{f}}{k_{b}}=K=\frac{C_{B}}{C_{A}}\\
& v_{0}=k_{f}\left ( C_{A} \right )_{eq}=k_{b}\left ( C_{B} \right )_{eq}\\
\end{split}


<pre><h2></font><font face="Segoe Script">Arrhenius Equation</font></h2></pre>
\begin{split}
& E_{A}:activation\ energy\\
& A:frequency factor\\
& \Delta E^{\ddagger }:standard\ internal\ energy\ of\ activation\\
& \Delta H^{\ddagger }:standard\ enthalpy\ of\ activation\\
& \Delta S^{\ddagger }:standard\ entropy\ of\ activation\\
& \Delta G^{\ddagger }:standard\ free\ energy\ of\ activation\\
& k=Ae^{\frac{-E_{A}}{RT}}\approx Ae^{\frac{-\Delta H^{\ddagger }}{RT}}=A^{'}e^{\frac{-\Delta G^{\ddagger }}{RT}}
\end{split}

<pre><h2><font face="Segoe Script">Effects of a potential change</font></h2></pre>

\begin{split}
& \alpha :transfer\ coefficient\\
& F:Faradaic\ Constant\\
& E^{0}:The\ formal\ potential\\
& C_{O}^{*},C_{R}^{*}:bulk\ concentrations\\
by\ \Delta G=-nFE :& \\
& \Delta G_{a}^{\ddagger }=\Delta G_{oa}^{\ddagger }-\left ( 1-\alpha  \right )F\left ( E-E^{0} \right ),
\Delta G_{c}^{\ddagger }=\Delta G_{oc}^{\ddagger }+\alpha F\left ( E-E^{0} \right )\\
by\ Arrhenius\ Equation:& \\
& k_{f}=A_{f}e^{-\frac{\Delta G_{c}^{\ddagger }}{RT}},k_{b}=A_{b}e^{-\frac{\Delta G_{a}^{\ddagger }}{RT}}\\
by\ f=\frac{F}{RT} ,so:& \\
& k_{f}=A_{f}e^{-\frac{\Delta G_{oc}^{\ddagger }}{RT}}e^{\left [-\alpha f\left ( E-E^{0} \right )  \right ]},
k_{b}=A_{b}e^{-\frac{\Delta G_{oa}^{\ddagger }}{RT}}e^{\left [\left ( 1-\alpha  \right )f\left ( E-E^{0} \right )  \right ]}\\
by\ equilibrium:\ &  \\
& E_{eq}=E^{0}\\
& k_{f}C_{O}^{*}=k_{b}C_{R}^{*}\\
& k^{0}=A_{f}e^{-\frac{\Delta G_{oc}^{\ddagger }}{RT}}=A_{b}e^{-\frac{\Delta G_{oa}^{\ddagger }}{RT}}\\
& i=nFAk^{0}\left [ C_{O}\left ( 0,t \right ) e^{-\alpha f\left ( E-E^{0} \right )}-C_{R}\left ( 0,t \right ) e^{\left (1-\alpha  \right ) f\left ( E-E^{0} \right )}\right ]
\end{split}

<h1><font face="Segoe Script">Application of B-V Equation</font></h1>
<pre><h2><font face="Segoe Script">Nernst Equation</font></h2></pre>
\begin{split}
when\ i=0:& \\
e^{f\left ( E_{eq}-E^{0} \right )}& =\frac{C_{O}^{*}}{C_{R}^{*}}\\
E_{eq}& =E^{0}+\frac{RT}{F}ln\left ( \frac{C_{O}^{*}}{C_{R}^{*}} \right )\\
\end{split}
<pre><h2><font face="Segoe Script">Current-Overpotential Equation</font></h2></pre>
\begin{split}
i_{0}& =i_{c} =i_{a}=nFAk^{0}C_{O}^{*}e^{-\alpha f\left ( E_{eq}-E^{0} \right )}=nFAk^{0}C_{O}^{\left ( 1-\alpha  \right )*}C_{R}^{*\alpha }\\
\frac{i}{i_{0}}& =
\left [ \frac{C_{O}\left ( 0,t \right ) e^{-\alpha f\left ( E-E^{0} \right )}}{C_{O}^{\left ( 1-\alpha  \right )*}C_{R}^{*\alpha }}-\frac{C_{R}\left ( 0,t \right ) e^{\left (1-\alpha  \right ) f\left ( E-E^{0} \right )}}{C_{O}^{\left ( 1-\alpha  \right )*}C_{R}^{*\alpha }}\right ]\\
& =\left [
\frac{C_{O}\left ( 0,t \right ) e^{-\alpha f\left ( E-E^{0} \right )}}{C_{O}^{*}}
\frac{C_{O}^{\alpha *}}{C_{R}^{*\alpha }}-
\frac{C_{R}\left ( 0,t \right ) e^{\left (1-\alpha  \right ) f\left ( E-E^{0} \right )}}{C_{R}^{*}}
\frac{C_{O}^{\left (\alpha -1  \right ) *}}{C_{R}^{*\left (\alpha -1 \right ) }}\right ]\\
& =\left [
\frac{C_{O}\left ( 0,t \right ) e^{-\alpha f\left ( E-E^{0} \right )}}{C_{O}^{*}}e^{\alpha f\left ( E_{eq}-E^{0} \right )}-
\frac{C_{R}\left ( 0,t \right ) e^{\left (1-\alpha  \right ) f\left ( E-E^{0} \right )}}{C_{R}^{*}}e^{\left (\alpha  - 1\right ) f\left ( E_{eq}-E^{0} \right )}\right ]\\
& =\left [
\frac{C_{O}\left ( 0,t \right ) }{C_{O}^{*}}e^{-\alpha f\left ( E-E_{eq} \right )}-
\frac{C_{R}\left ( 0,t \right ) }{C_{R}^{*}}e^{\left (1-\alpha  \right ) f\left ( E-E_{eq} \right )}\right ]\\
\end{split}
<pre><h2><font face="Segoe Script">Nernst Equation Transform</font></h2></pre>
\begin{split}
when\  i_{0}\gg i:& \\
\frac{C_{O}\left ( 0,t \right ) }{C_{R}\left ( 0,t \right )}& =
\frac{ C_{O}^{*}}{C_{R}^{*}}e^{ f\left ( E-E_{eq} \right )} \\
by\ e^{f\left ( E_{eq}-E^{0} \right )}=\frac{C_{O}^{*}}{C_{R}^{*}}: & \\
\frac{C_{O}\left ( 0,t \right ) }{C_{R}\left ( 0,t \right )}& = e^{ f\left ( E-E^{0} \right )} \\
E & =E^{0}+\frac{RT}{F}ln\left ( \frac{C_{O}\left ( 0,t \right )}{C_{R}\left ( 0,t \right )} \right )\\
\end{split}

<pre><h2><font face="Segoe Script">Tafel Equation</font></h2></pre>
\begin{split}
when\ \frac{C_{O}\left ( 0,t \right ) }{C_{O}^{*}},\frac{C_{R}\left ( 0,t \right ) }{C_{R}^{*}}=0.9~1.1： & \\
\frac{i}{i_{0}}& =\left [
\frac{C_{O}\left ( 0,t \right ) }{C_{O}^{*}}e^{-\alpha f\left ( E-E_{eq} \right )}-
\frac{C_{R}\left ( 0,t \right ) }{C_{O}^{*}}e^{\left (1-\alpha  \right ) f\left ( E-E^{eq} \right )}\right ]\\
& =\left [e^{-\alpha f\left ( E-E_{eq} \right )}-e^{\left (1-\alpha  \right ) f\left ( E-E^{eq} \right )}\right ]\\
by\ e^{x}\approx 1+x,when\ small\ x:& \\
\frac{i}{i_{0}}& =\left [1-\alpha f\left ( E-E_{eq} \right )-1-\left (1-\alpha  \right ) f\left ( E-E^{eq} \right )\right ]\\
& =-f\left ( E-E^{eq} \right )\\
when\ big\ x:& \\
e^{-\alpha f\left ( E-E_{eq} \right )}& \gg e^{\left (1-\alpha  \right ) f\left ( E-E^{eq} \right )}\\
\frac{i}{i_{0}}& =e^{-\alpha f\left ( E-E_{eq} \right )}\\
\eta & =E-E_{eq}=\frac{RT}{\alpha F}ln \left (i_{0}  \right )-\frac{RT}{\alpha F}ln \left (i  \right )
\end{split}
<pre><h2><font face="Segoe Script">the charge-transfer resistance</font></h2></pre>
\begin{split}
R_{ct}=-\frac{E-E_{eq}}{i}=\frac{RT}{Fi_{0}}
\end{split}
<h1><font face="Segoe Script">Nernst-Planck equation</font></h1>
\begin{split}
J_{i}\left ( x \right )& :the\ flux\ of\ species\ i\left ( mol\ s^{-1}cm^{-2} \right )\\
D_{i}& :the\ diffusion\ coefficient\ \left ( cm^{2}/s \right )\\
\phi \left ( x \right )& :potential\\
z_{i}& :charge\ of\ species\ i\\
C_{i}& :concentration\ of\ species\ i\\
A& :area\\
v\left ( x \right )& :the\ solution\ velocity\\
J_{i}\left ( x \right )& =-D_{i}\frac{\partial C_{i}\left ( x \right )}{\partial x}-\frac{z_{i}F}{RT}D_{i}C_{i}\frac{\partial \phi \left ( x \right )}{\partial x}+C_{i}v\left ( x \right )\\
\end{split}
<pre><h2><font face="Segoe Script">Fick's laws of diffusion</font></h2></pre>
\begin{split}
J_{O}\left ( x \right )& =-D_{O}\frac{\partial C_{O}\left ( x,t \right )}{\partial x}\\
\frac{\partial C_{O}\left ( x,t \right )}{\partial t}& =
\frac{J\left ( x,t \right )-J\left ( x+dx,t \right )}{dx}\\
& =-\frac{J\left ( x,t \right )}{\partial x}=\frac{\partial }{\partial x}\left [ D_{O}\frac{\partial C_{O}\left ( x,t \right )}{\partial x} \right ]
\end{split}
<pre><h2><font face="Segoe Script">Diffusion and Migration currents</font></h2></pre>
\begin{split}
when\ v\left ( x \right )=0& :\\
-J_{j}& =\frac{i_{j}}{z_{j}FA}=\frac{i_{d,j}}{z_{j}FA}+\frac{i_{m,j}}{z_{j}FA}\\
\frac{i_{d,j}}{z_{j}FA}& =D_{j}\frac{\partial C_{j}}{\partial x}\\
\frac{i_{m,j}}{z_{j}FA}& =\frac{z_{j}FD_{j}}{RT}C_{j}\frac{\partial \phi }{\partial x}\\
\end{split}
<h1><font face="Segoe Script">Steady-State Mass Transfer</font></h1>
\begin{split}
\delta _{o}& :the\ thickness\ of\ nernst\ diffusion\ layer\\
C^{*}& =C\left ( \delta _{o},t \right )\\
m_{o}& =D_{o}/\delta _{o}\\
v_{mt}& =D_{o}/\delta _{o}\left [ C^{*}_{o}-C_{o}\left ( x=0 \right ) \right ]\\
& =m_{o}\left [ C^{*}_{o}-C_{o}\left ( x=0 \right ) \right ]
\end{split}
<pre><h2><font face="Segoe Script">limiting current</font></h2></pre>
\begin{split}
when\ C_{O}\left ( x=0 \right )=0,C_{R}\left ( x=0 \right )\gg C_{R}^{*} & :\\
\frac{i}{nFA}=m_{O}\left [ C^{*}_{o}-C_{o}\left ( x=0 \right ) \right ],&
\frac{i}{nFA}=m_{R}\left [ C_{R}\left ( x=0 \right )-C^{*}_{R}\right ]\\
i_{l,c}=nFAm_{O}  C^{*}_{O},&
i_{l,r}=nFAm_{R}  C^{*}_{R} \\
so:& \\
\frac{C_{O}\left ( x=0 \right )}{C^{*}_{O}}=1-\frac{i}{i_{l,c}}, &
\frac{C_{R}\left ( x=0 \right )}{C^{*}_{R}}=1-\frac{i}{i_{l,r}}
\end{split}
<pre><h2><font face="Segoe Script">the mass-transfer resistance</font></h2></pre>
\begin{split}
by\ Current-Overpotential\ Equation & : \\
\frac{i}{i_{0}}& = \left [
\left (1-\frac{i}{i_{l,c}}  \right )e^{-\alpha f\left ( E-E_{eq} \right )}-
\left (1-\frac{i}{i_{l,r}}  \right )e^{\left (1-\alpha  \right ) f\left ( E-E_{eq} \right )}\right ]\\
by\ Taylor\ formula:& \\
g[C_{O}\left (0,t \right ),C_{R}\left (0,t \right ),\eta ]& =
\frac{i}{i_{0}} =\left [
\left (1-\frac{i}{i_{l,c}}  \right )e^{-\alpha f\left ( E-E_{eq} \right )}-
\left (1-\frac{i}{i_{l,r}}  \right )e^{\left (1-\alpha  \right ) f\left ( E-E_{eq} \right )}\right ]\\
\frac{i}{i_{0}}& =\left [ \delta C_{O}\left ( 0,t \right )\frac{\partial }{\partial C_{O}\left ( 0,t \right )} +\delta C_{R}\left ( 0,t \right )\frac{\partial }{\partial C_{R}\left ( 0,t \right )}+\delta \eta\frac{\partial }{\partial \eta} \right ]g[C_{O}\left (0,t \right ),C_{R}\left (0,t \right ),\eta ]\\
when\ at\ point\ \left ( C_{O}^{*},C_{R}^{*},\eta =0  \right ):& \\
\frac{i}{i_{0}}& =\frac{\delta C_{O}\left ( 0,t \right )}{C_{O}^{*}}-\frac{\delta C_{R}\left ( 0,t \right )}{C_{R}^{*}}-f\delta \eta \\
\eta & =i\frac{RT}{F}\left ( \frac{1}{i_{l,r}}-\frac{1}{i_{l,c}}-\frac{1}{i_{o}} \right )\\
& =-i\left ( R_{ct}+R_{mt,c}+R_{mt,r} \right )
\end{split}
</body>
</html>
