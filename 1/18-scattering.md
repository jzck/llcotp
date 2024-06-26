---
title: 18-scattering
---
§18. Scattering
As already mentioned in §17, a complete calculation of the result of a
collision between two particles (i.e. the determination of the angle x) requires
the solution of the equations of motion for the particular law of interaction
involved.
We shall first consider the equivalent problem of the deflection of a single
particle of mass m moving in a field U(r) whose centre is at rest (and is at
the centre of mass of the two particles in the original problem).
As has been shown in $14, the path of a particle in a central field is sym-
metrical about a line from the centre to the nearest point in the orbit (OA
in Fig. 18). Hence the two asymptotes to the orbit make equal angles (o,
say) with this line. The angle X through which the particle is deflected as it
passes the centre is seen from Fig. 18 to be
X = -200.
(18.1)
A
X
to
FIG. 18
The angle do itself is given, according to (14.7), by
(M/r2) dr
(18.2)
taken between the nearest approach to the centre and infinity. It should be
recalled that rmin is a zero of the radicand.
For an infinite motion, such as that considered here, it is convenient to
use instead of the constants E and M the velocity Voo of the particle at infinity
and the impact parameter p. The latter is the length of the perpendicular
from the centre O to the direction of Voo, i.e. the distance at which the particle
would pass the centre if there were no field of force (Fig. 18). The energy
and the angular momentum are given in terms of these quantities by
E = 1mvoo²,
M = mpVoo,
(18.3)
§18
Scattering
49
and formula (18.2) becomes
dr
(18.4)
Together with (18.1), this gives X as a function of p.
In physical applications we are usually concerned not with the deflection
of a single particle but with the scattering of a beam of identical particles
incident with uniform velocity Voo on the scattering centre. The different
particles in the beam have different impact parameters and are therefore
scattered through different angles X. Let dN be the number of particles
scattered per unit time through angles between X and X + dx. This number
itself is not suitable for describing the scattering process, since it is propor-
tional to the density of the incident beam. We therefore use the ratio
do = dN/n,
(18.5)
where n is the number of particles passing in unit time through unit area of
the beam cross-section (the beam being assumed uniform over its cross-
section). This ratio has the dimensions of area and is called the effective
scattering cross-section. It is entirely determined by the form of the scattering
field and is the most important characteristic of the scattering process.
We shall suppose that the relation between X and P is one-to-one; this is
so if the angle of scattering is a monotonically decreasing function of the
impact parameter. In that case, only those particles whose impact parameters
lie between p(x) and p(x) + dp(x) are scattered at angles between X and
+ dx. The number of such particles is equal to the product of n and the
area between two circles of radii P and p+dp, i.e. dN = 2mp dp n. The
effective cross-section is therefore
do = 2mp dp.
(18.6)
In order to find the dependence of do on the angle of scattering, we need
only rewrite (18.6) as
do = 2(x)|dp(x)/dx|dx
(18.7)
Here we use the modulus of the derivative dp/dx, since the derivative may
be (and usually is) negative. t Often do is referred to the solid angle element
do instead of the plane angle element dx. The solid angle between cones
with vertical angles X and x+dx is do = 2n sin x dx. Hence we have from
(18.7)
do.
(18.8)
t If the function p(x) is many-valued, we must obviously take the sum of such expressions
as (18.7) over all the branches of this function.
50
Collisions Between Particles
§18
Returning now to the problem of the scattering of a beam of particles, not
by a fixed centre of force, but by other particles initially at rest, we can say
that (18.7) gives the effective cross-section as a function of the angle of
scattering in the centre-of-mass system. To find the corresponding expression
as a function of the scattering angle 0 in the laboratory system, we must
express X in (18.7) in terms of 0 by means of formulae (17.4). This gives
expressions for both the scattering cross-section for the incident beam of
particles (x in terms of 01) and that for the particles initially at rest (x in terms
of O2).
PROBLEMS
PROBLEM 1. Determine the effective cross-section for scattering of particles from a perfectly
rigid sphere of radius a (i.e. when the interaction is such that U = 8 for r < a and U = 0
for r>a).
SOLUTION. Since a particle moves freely outside the sphere and cannot penetrate into it,
the path consists of two straight lines symmetrical about the radius to the point where the
particle strikes the sphere (Fig. 19). It is evident from Fig. 19 that
a sin to = a sin 1(-x) = a cos 1x.
A
to
p
&
FIG. 19
Substituting in (18.7) or (18.8), we have
do = 1ma2 sin X do,
(1)
i.e. the scattering is isotropic in the C system. On integrating do over all angles, we find that
the total cross-section o = na2, in accordance with the fact that the "impact area" which the
particle must strike in order to be scattered is simply the cross-sectional area of the sphere.
In order to change to the L system, X must be expressed in terms of 01 by (17.4). The
calculations are entirely similar to those of $16, Problem 2, on account of the formal resemb-
lance between formulae (17.4) and (16.5). For M1 < m2 (where M1 is the mass of the particle
and m2 that of the sphere) we have
do1,
where do1 = 2n sin 01 d01. If, on the other hand, M2 < M1, then
For m1 = M2, we have do = a²|cos 01| do1, which can also be obtained directly by sub-
stituting X = 201 from (17.9) in (1).
§18
Scattering
51
For a sphere originally at rest, X = n-202 in all cases, and substitution in (1) gives
do2 = a2|cos 02 do2.
PROBLEM 2. Express the effective cross-section (Problem 1) as a function of the energy E
lost by a scattered particle.
SOLUTION. The energy lost by a particle of mass M1 is equal to that gained by the sphere of
mass M2. From (17.5) and (17.7), € = E2' = [2m22m2/(m1+m2)2] voo2 sin21x = Emax sin21x,
whence de = 1 mex sin X dx; substituting in (1), Problem 1, we have do = na2 de/emax. The
scattered particles are uniformly distributed with respect to € in the range from zero to
Emax.
PROBLEM 3. Find the effective cross-section as a function of the velocity Uoo for particles
scattered in a field U -rrn.
SOLUTION. According to (10.3), if the potential energy is a homogeneous function of order
k = -n, then similar paths are such that p ~v-2/n, or p = Voo-2/nf(x), the angles of deflec-
tion X being equal for similar paths. Substitution in (18.6) gives do ~ Voo-4/n do.
PROBLEM 4. Determine the effective cross-section for a particle to "fall" to the centre of
a field U = -a/r2.
SOLUTION. The particles which "fall" to the centre are those for which 2a > mp20002 (see
(14.11)), i.e. for which the impact parameter does not exceed Pmax = (2a/mvoo). The
effective cross-section is therefore o = Pmax2 = 2na/mvo².
PROBLEM 5. The same as Problem 4, but for a field U = -a/rn (n 2, a > 0).
SOLUTION. The effective potential energy Ueff = depends on r in the
manner shown in Fig. 20. Its maximum value is
Ueff
U0
FIG. 20
The particles which "fall" to the centre are those for which U0 < E. The condition U0 = E
gives Pmax, whence
=
PROBLEM 6. Determine the effective cross-section for particles of mass m1 to strike a sphere
of mass m2 and radius R to which they are attracted in accordance with Newton's law.
SOLUTION. The condition for a particle to reach the sphere is that rmin < R, where r'min
is the point on the path which is nearest to the centre of the sphere. The greatest possible
value of P is given by rmin = R; this is equivalent to Ueff(R) = E or
= , where a = ymim2 (2 being the gravitational constant) and we have put m 22 M1 on
the assumption that m2 > M1. Solving for pmax2, we finally obtain o = mR2(1+2ym2/Rvv3).
52
Collisions Between Particles
§18
When
Voo
8 the effective cross-section tends, of course, to the geometrical cross-section
of the sphere.
PROBLEM 7. Deduce the form of a scattering field U(r), given the effective cross-section
as a function of the angle of scattering for a given energy E. It is assumed that U(r) decreases
monotonically with r (a repulsive field), with U(0) > E and U(00) = 0 (O. B. FIRSOV 1953).
SOLUTION. Integration of do with respect to the scattering angle gives, according to the
formula
(1)
the square of the impact parameter, so that p(x) (and therefore x(p)) is known.
We put
s=1/r,
=1/p2,
[[1-(U|E)]
(2)
Then formulae (18.1), (18.2) become
1/
(3)
where so(x) is the root of the equation xw2(so)-so2 = 0.
Equation (3) is an integral equation for the function w(s), and may be solved by a method
similar to that used in $12. Dividing both sides of (3) by (a-x) and integrating with respect
to x from zero to a, we find
so(a)
dx ds
so(a)
ds
or, integrating by parts on the left-hand side,
This relation is differentiated with respect to a, and then so(a) is replaced by s simply;
accordingly a is replaced by s2/w2, and the result is, in differential form,
=
(11/20)
or
dx
This equation can be integrated immediately if the order of integration on the right-hand
side is inverted. Since for S = 0 (i.e. r oo) we must have W = 1 (i.e. U = 0), we have,
