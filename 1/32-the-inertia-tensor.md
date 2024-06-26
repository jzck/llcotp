---
title: 32-the-inertia-tensor
---
rotate with angular velocities S which are equal in magnitude and parallel
in direction. This enables us to call S the angular velocity of the body. The
velocity of the translational motion, however, does not have this "absolute"
property.
It is seen from the first formula (31.3) that, if V and S are, at any given
instant, perpendicular for some choice of the origin O, then V' and SS are
perpendicular for any other origin O'. Formula (31.2) shows that in this case
the velocities V of all points in the body are perpendicular to S. It is then
always possible+ to choose an origin O' whose velocity V' is zero, SO that the
motion of the body at the instant considered is a pure rotation about an axis
through O'. This axis is called the instantaneous axis of rotation.t
In what follows we shall always suppose that the origin of the moving
system is taken to be at the centre of mass of the body, and so the axis of
rotation passes through the centre of mass. In general both the magnitude
and the direction of S vary during the motion.
$32. The inertia tensor
To calculate the kinetic energy of a rigid body, we may consider it as a
discrete system of particles and put T = mv2, where the summation is
taken over all the particles in the body. Here, and in what follows, we simplify
the notation by omitting the suffix which denumerates the particles.
Substitution of (31.2) gives
T = Sxx+
The velocities V and S are the same for every point in the body. In the first
term, therefore, V2 can be taken outside the summation sign, and Em is
just the mass of the body, which we denote by u. In the second term we put
EmV Sxr = Emr VxS = VxS Emr. Since we take the origin of the
moving system to be at the centre of mass, this term is zero, because Emr = 0.
Finally, in the third term we expand the squared vector product. The result
is
(32.1)
Thus the kinetic energy of a rigid body can be written as the sum of two
parts. The first term in (32.1) is the kinetic energy of the translational motion,
and is of the same form as if the whole mass of the body were concentrated
at the centre of mass. The second term is the kinetic energy of the rotation
with angular velocity S about an axis passing through the centre of mass.
It should be emphasised that this division of the kinetic energy into two parts
is possible only because the origin of the co-ordinate system fixed in the
body has been taken to be at its centre of mass.
t O' may, of course, lie outside the body.
+ In the general case where V and SC are not perpendicular, the origin may be chosen so
as to make V and S parallel, i.e. so that the motion consists (at the instant in question) of a
rotation about some axis together with a translation along that axis.
§32
The inertia tensor
99
We may rewrite the kinetic energy of rotation in tensor form, i.e. in terms
of the components Xi and O of the vectors r and L. We have
Here we have used the identity Oi = SikOk, where dik is the unit tensor,
whose components are unity for i = k and zero for i # k. In terms of the
tensor
(32.2)
we have finally the following expression for the kinetic energy of a rigid
body:
T =
(32.3)
The Lagrangian for a rigid body is obtained from (32.3) by subtracting
the potential energy:
L =
(32.4)
The potential energy is in general a function of the six variables which define
the position of the rigid body, e.g. the three co-ordinates X, Y, Z of the
centre of mass and the three angles which specify the relative orientation of
the moving and fixed co-ordinate axes.
The tensor Iik is called the inertia tensor of the body. It is symmetrical,
i.e.
Ik=Iki
(32.5)
as is evident from the definition (32.2). For clarity, we may give its com-
ponents explicitly:
TEST
(32.6)
m(x2+y2)
The components Ixx, Iyy, Izz are called the moments of inertia about the
corresponding axes.
The inertia tensor is evidently additive: the moments of inertia of a body
are the sums of those of its parts.
t In this chapter, the letters i, k, l are tensor suffixes and take the values 1, 2, 3. The
summation rule will always be used, i.e. summation signs are omitted, but summation over
the values 1, 2, 3 is implied whenever a suffix occurs twice in any expression. Such a suffix is
called a dummy suffix. For example, AiBi = A . B, Ai2 = AiA1 = A², etc. It is obvious that
dummy suffixes can be replaced by any other like suffixes, except ones which already appear
elsewhere in the expression concerned.
100
Motion of a Rigid Body
§32
If the body is regarded as continuous, the sum in the definition (32.2)
becomes an integral over the volume of the body:
(32.7)
Like any symmetrical tensor of rank two, the inertia tensor can be reduced
to diagonal form by an appropriate choice of the directions of the axes
X1, x2, X3. These directions are called the principal axes of inertia, and the
corresponding values of the diagonal components of the tensor are called the
principal moments of inertia; we shall denote them by I, I2, I3. When the
axes X1, X2, X3 are so chosen, the kinetic energy of rotation takes the very
simple form
=
(32.8)
None of the three principal moments of inertia can exceed the sum of the
other two. For instance,
m(x12+x22) = I3.
(32.9)
A body whose three principal moments of inertia are all different is called
an asymmetrical top. If two are equal (I1 = I2 # I3), we have a symmetrical
top. In this case the direction of one of the principal axes in the x1x2-plane
may be chosen arbitrarily. If all three principal moments of inertia are equal,
the body is called a spherical top, and the three axes of inertia may be chosen
arbitrarily as any three mutually perpendicular axes.
The determination of the principal axes of inertia is much simplified if
the body is symmetrical, for it is clear that the position of the centre of mass
and the directions of the principal axes must have the same symmetry as
the body. For example, if the body has a plane of symmetry, the centre of
mass must lie in that plane, which also contains two of the principal axes of
inertia, while the third is perpendicular to the plane. An obvious case of this
kind is a coplanar system of particles. Here there is a simple relation between
the three principal moments of inertia. If the plane of the system is taken as
the x1x2-plane, then X3 = 0 for every particle, and so I = mx22, I2 = 12,
I3 = (12+x2)2, whence
(32.10)
If a body has an axis of symmetry of any order, the centre of mass must lie
on that axis, which is also one of the principal axes of inertia, while the other
two are perpendicular to it. If the axis is of order higher than the second,
the body is a symmetrical top. For any principal axis perpendicular to the
axis of symmetry can be turned through an angle different from 180° about the
latter, i.e. the choice of the perpendicular axes is not unique, and this can
happen only if the body is a symmetrical top.
A particular case here is a collinear system of particles. If the line of the
system is taken as the x3-axis, then X1 = X2 = 0 for every particle, and so
§32
The inertia tensor
101
two of the principal moments of inertia are equal and the third is zero:
I3 = 0.
(32.11)
Such a system is called a rotator. The characteristic property which distin-
guishes a rotator from other bodies is that it has only two, not three, rotational
degrees of freedom, corresponding to rotations about the X1 and X2 axes: it
is clearly meaningless to speak of the rotation of a straight line about itself.
Finally, we may note one further result concerning the calculation of the
inertia tensor. Although this tensor has been defined with respect to a system
of co-ordinates whose origin is at the centre of mass (as is necessary if the
fundamental formula (32.3) is to be valid), it may sometimes be more con-
veniently found by first calculating a similar tensor I' =
defined with respect to some other origin O'. If the distance OO' is repre-
sented by a vector a, then r = r'+a, Xi = x'i+ai; since, by the definition
of O, Emr = 0, we have
I'ikIk(a2ik-aiak).
(32.12)
Using this formula, we can easily calculate Iik if I'ik is known.
PROBLEMS
PROBLEM 1. Determine the principal moments of inertia for the following types of mole-
cule, regarded as systems of particles at fixed distances apart: (a) a molecule of collinear
atoms, (b) a triatomic molecule which is an isosceles triangle (Fig. 36), (c) a tetratomic
molecule which is an equilateral-based tetrahedron (Fig. 37).
m2
X2
m2
h
x
m
a
a
m
a
m
m
a
FIG. 36
FIG. 37
SOLUTION. (a)
Is = 0,
where Ma is the mass of the ath atom, lao the distance between the ath and bth atoms, and
the summation includes one term for every pair of atoms in the molecule.
For a diatomic molecule there is only one term in the sum, and the result is obvious it is
the product of the reduced mass of the two atoms and the square of the distance between
them: I1 = I2 = m1m2l2((m1+m2).
(b) The centre of mass is on the axis of symmetry of the triangle, at a distance X2 = mzh/u
from its base (h being the height of the triangle). The moments of inertia are I1 = 2m1m2h2/u,
I2 = 1m1a2, I3 = I+I2.
(c) The centre of mass is on the axis of symmetry of the tetrahedron, at a distance
X3 = mgh/u from its base (h being the height of the tetrahedron). The moments of inertia
102
Motion of a Rigid Body
§32
are I1 = = I3 = mia². If M1 = M2, h = (2/3)a, the molecule is a
regular tetrahedron and I1=I2 = I3 = mia2.
PROBLEM 2. Determine the principal moments of inertia for the following homogeneous
bodies: (a) a thin rod of length l, (b) a sphere of radius R, (c) a circular cylinder of radius R
and height h, (d) a rectangular parallelepiped of sides a, b, and c, (e) a circular cone of height
h and base radius R, (f) an ellipsoid of semiaxes a, b, c.
SOLUTION. (a) I1 = I2 = Trul2, I3 = 0 (we neglect the thickness of the rod).
(b) I1 = I2 = I3 = zuR2 (found by calculating the sum I+I+I3 = 2p dV).
(c) I1 = I2 = tu(R2+th2), I3 = tuR2 (where the x3-axis is along the axis of the cylinder).
(d) I1 = (2+c2), I2 = (a2+cc), I3 = 121(a2++b) (where the axes X1, x2, X3 are
along the sides a, b, c respectively).
(e) We first calculate the tensor I'ik with respect to axes whose origin is at the vertex of
the cone (Fig. 38). The calculation is simple if cylindrical co-ordinates are used, and the result
is I'1 = I'2 = I'3 = 2 The centre of mass is easily shown to be on the
axis of the cone and at a distance a = 3h from the vertex. Formula (32.12) therefore gives
I1 = I2 = I'1-2 = I3 = I'3 = TouR2.
X3,X3'
X2
xi
x2
FIG. 38
(f) The centre of mass is at the centre of the ellipsoid, and the principal axes of inertia are
along the axes of the ellipsoid. The integration over the volume of the ellipsoid can be reduced
to one over a sphere by the transformation x = as,y = bn, 2 = c5, which converts the equa-
tion of the surface of the ellipsoid 1 into that of the unit sphere
st+24's = 1.
For example, the moment of inertia about the x-axis is
dz
= tabcI'(b2 tc2),
where I' is the moment of inertia of a sphere of unit radius. Since the volume of the ellipsoid
is 4nabc/3, we find the moments of inertia I = tu(b2+c2), I2 = tu(a2+c2), I3 = tu(a2+b2).
PROBLEM 3. Determine the frequency of small oscillations of a compound pendulum (a
rigid body swinging about a fixed horizontal axis in a gravitational field).
SOLUTION. Let l be the distance between the centre of mass of the pendulum and the axis
about which it rotates, and a, B, y the angles between the principal axes of inertia and the
axis of rotation. We take as the variable co-ordinate the angle between the vertical
and a line through the centre of mass perpendicular to the axis of rotation. The velocity of
the centre of mass is V = 10, and the components of the angular velocity along the principal
§32
The inertia tensor
103
axes of inertia are o cos a, b cos B, b cos y. Assuming the angle to be small, we find the
potential energy U = ugl(1-cos 9 22 12. The Lagrangian is therefore
=
The frequency of the oscillations is consequently
w2 = cos2y).
PROBLEM 4. Find the kinetic energy of the system shown in Fig. 39: OA and AB are thin
uniform rods of length l hinged together at A. The rod OA rotates (in the plane of the diagram)
about O, while the end B of the rod AB slides along Ox.
A
l
l
x
B
FIG. 39
SOLUTION. The velocity of the centre of mass of the rod OA (which is at the middle of
the rod) is 110, where is the angle AOB. The kinetic energy of the rod OA is therefore
T1 = where u is the mass of each rod.
The Cartesian co-ordinates of the centre of mass of the rod AB are X = sl cos o, Y
= 1/ sin b. Since the angular velocity of rotation of this rod is also b, its kinetic energy is
T2 = = tul2(1- +8 sin2o)62 +1162. The total kinetic energy of this
system is therefore = I = Tzul2 (see Problem 2(a)).
PROBLEM 5. Find the kinetic energy of a cylinder of radius R rolling on a plane, if the mass
of the cylinder is so distributed that one of the principal axes of inertia is parallel to the axis
of the cylinder and at a distance a from it, and the moment of inertia about that principal
axis is I.
SOLUTION. Let be the angle between the vertical and a line from the centre of mass
perpendicular to the axis of the cylinder (Fig. 40). The motion of the cylinder at any instant
R
FIG. 40
may be regarded as a pure rotation about an instantaneous axis which coincides with the
line where the cylinder touches the plane. The angular velocity of this rotation is o, since
the angular velocity of rotation about all parallel axes is the same. The centre of mass is at a
distance V(a2+R2-2aR cos ) from the instantaneous axis, and its velocity is therefore
V = bv /(a2+R2-2aR cos ). The total kinetic energy is
T = cos
104
Motion of a Rigid Body
§32
PROBLEM 6. Find the kinetic energy of a homogeneous cylinder of radius a rolling inside
a cylindrical surface of radius R (Fig. 41).
R
FIG. 41
SOLUTION. We use the angle between the vertical and the line joining the centres of the
cylinders. The centre of mass of the rolling cylinder is on the axis, and its velocity is V =
o(R-a). We can calculate the angular velocity as that of a pure rotation about an instantaneous
axis which coincides with the line of contact of the cylinders it is Q = V/a = p(R-a)/a.
If I3 is the moment of inertia about the axis of the cylinder, then
T =
I3 being given by Problem 2(c).
PROBLEM 7. Find the kinetic energy of a homogeneous cone rolling on a plane.
SOLUTION. We denote by 0 the angle between the line OA in which the cone touches the
plane and some fixed direction in the plane (Fig. 42). The centre of mass is on the axis of the
cone, and its velocity V = a0 cos a, where 2a is the vertical angle of the cone and a the
Z
Y
A
FIG. 42
distance of the centre of mass from the vertex. The angular velocity can be calculated as
that of a pure rotation about the instantaneous axis OA: S2 = V/a sin a = é cot a. One of
the principal axes of inertia (x3) is along the axis of the cone, and we take another (x2) perpen-
dicular to the axis of the cone and to the line OA. Then the components of the vector S
(which is parallel to OA) along the principal axes of inertia are O sin a, 0, O cos a. The kinetic
energy is thus
=
= 3uh202(1+5 cos2x)/40,
where h is the height of the cone, and I1, I3 and a have been given in Problem 2(e).
PROBLEM 8. Find the kinetic energy of a homogeneous cone whose base rolls on a plane
and whose vertex is fixed at a height above the plane equal to the radius of the base, so that
the axis of the cone is parallel to the plane.
SOLUTION. We use the angle 0 between a fixed direction in the plane and the projection
of the axis of the cone on the plane (Fig. 43). Then the velocity of the centre of mass is V = aß,
