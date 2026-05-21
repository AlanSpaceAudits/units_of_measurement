# Internal Consistency of the Astronomical System

Null-hypothesis statement for the brief in this repository, *A System of
Mutually Reliant Ratios Creates the Internal Consistency of the System*
(`units_of_measurement.pdf`).

## The question

The astronomical distance scale rests on a small set of constants that feed
one another: the speed of light *c*, the astronomical unit, the solar
parallax, the constant of aberration, and the light-time of the AU. They
agree with each other to many digits. Does that agreement verify their
absolute values, or does it only show that the system is internally
consistent?

## Null hypothesis

**H₁:** The mutual agreement of the astronomical constants is independent
empirical verification of their absolute values.

**H₀:** The mutual agreement of the astronomical constants follows
necessarily from their definitional interdependence, so it demonstrates the
system's internal consistency and verifies no absolute value.

## A distance is a ratio, not a direct measurement

No astronomical distance is read off an instrument. It is computed from an
angle and a known length by trigonometry, and a triangle is fixed only when
two of its three parts are supplied. The parallax relation `d = R / sin(θ)`
returns a distance only once a baseline radius *R* is fed in. The angle alone
fixes nothing. Multiply *R* by any factor and every distance built on it
multiplies by the same factor, while every observed angle stays put. The
choice of length unit is therefore free.

This was tested by deriving the whole distance ladder twice: once in the
Chinese li (the unit of the Gai Tian survey, fixed by Yi Xing in 724 AD) and
once in the metric metre. The Moon, the Sun, the planets, and the speed of
light come out as definite numbers in each system. They differ only by a
single conversion factor, and every li value multiplied by that factor
reproduces the metre value exactly, because the underlying angle factors are
identical in both systems. The two unit ladders are one ladder.

## The conversion factor exists by construction

The li and the metre are each defined as a fraction of one circle, the
Earth's girth: the li from Yi Xing's meridian survey (351.267 li per du), the
metre from the 1791 quadrant definition. Dividing the two circumference
values yields the conversion factor (1 li is about 312.35 m). The factor is
not measured; it is the ratio of two definitions of the same circle.
Equivalence between the unit systems is then automatic. It shows that the
systems are consistent, and nothing about whether either absolute scale is
correct.

## The aberration route returns its own input

The astronomical unit can be reached two ways. Parallax gives it as the
Earth's radius over the sine of the solar parallax. Aberration gives it
through `tan(κ) = v/c` with the orbital speed `v = 2π·AU/T`, the route
Foucault ran in 1862 from a measured *c* and Bradley's aberration constant.
The two routes agree. They agree because the aberration constant and the
solar parallax are both pinned to the AU already: the aberration constant is
the slice of the observed stellar oscillation for which `c·tan(κ)` equals the
assumed orbital velocity `2π·AU/T`. In 1805 Laplace had Delambre redetermine
the light constant from the eclipses of Jupiter's moon Io, and Delambre
returned exactly Bradley's aberration figure. The agreement of the routes is
the identity handing back what was put into it, not a second, independent
confirmation.

## The metre and c are an algebra switch

Until 1983 the metre was the standard and *c* was measured against it. In
1983 *c* was fixed at exactly 299,792,458 m/s and the metre was redefined as
the distance light travels in `1/c` seconds. The number was chosen so the new
metre equals the old one. Which quantity is held fixed changed; the length
did not. A definitional substitution cannot verify a length.

## Newcomb and de Sitter said it on the page

Newcomb (1895) adjusted the speed of light, the AU, the solar parallax, and
the aberration constant jointly, in a single least-squares fit, so each value
already carried the others. de Sitter (1938, p. 213) stated the result
directly: an ideal system would have every constant agree with its observed
value while the theoretical relations held rigorously, and "our present
system is not consistent." His p. 214 footnote: the constants "are, of
course, dependent on each other through observations." The agreement among
the constants is interdependence acknowledged by the people who assembled
them.

## Conclusion

Failed to falsify H₀. Every route into the astronomical distance scale was
found to be a chain of ratios closing on inputs already inside the system.
Running the ladder in two unrelated length units changes only the labels.
The unit conversion is the ratio of two definitions of one circle. The
aberration determination of the AU returns the AU its own constant was
extracted from. The 1983 metre is a definitional substitution. Newcomb fitted
the constants jointly and de Sitter conceded the interdependence in print. No
step verified an absolute distance or speed against anything outside the
system. The agreement is internal consistency, which H₀ asserts and H₁
denies.

## Falsification condition

H₀ is falsified by a single measurement of one absolute value (the AU, *c*,
or a parallax) obtained without assuming any of the others. The transit and
radar determinations of the AU assume the parallax geometry or a known *c*;
the aberration route assumes the orbital velocity; light-time methods assume
*c*. Each draws on the rest. Until one absolute value is fixed by a method
that stands free of the others, H₀ stands.

## Sources

Bradley, J. (1728). An account of a new discovered motion of the fixed stars.
*Philosophical Transactions of the Royal Society*, 35, 637-661.

de Sitter, W. & Brouwer, D. (1938). On the system of astronomical constants.
*Bulletin of the Astronomical Institutes of the Netherlands*, 8(307),
213-231.

Foucault, L. (1862). Détermination expérimentale de la vitesse de la
lumière; parallaxe du Soleil. *Comptes Rendus de l'Académie des Sciences*,
55, 501-503.

Laplace, P.-S. (1805). *Traité de Mécanique Céleste, Tome IV: Théorie des
satellites de Jupiter*. Paris: Courcier.

Newcomb, S. (1895). *The Elements of the Four Inner Planets and the
Fundamental Constants of Astronomy*. Washington, DC: Government Printing
Office.
