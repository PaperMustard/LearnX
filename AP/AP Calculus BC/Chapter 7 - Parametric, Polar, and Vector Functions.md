
> **AP Exam Weight**: 10-15% | Multiple Choice: 4-6 questions | Free Response: Parts of several questions

## 📚 Table of Contents
1. [Parametric Functions]
2. [Polar Coordinates]
3. [Vector Functions]
4. [Motion in Space]
5. [Applications]

## 1. Parametric Functions 📊

### Understanding Parametric Functions
A way to describe curves using parameter t. Think of it as:
- Motion over time
- Coordinated x and y movement
- Path tracing
- Indirect curve description

### Basic Form
x = f(t), y = g(t)

#### Key Concepts
1. **Parameter t**:
   - Independent variable
   - Often represents time
   - Controls both x and y
   - Defines curve position

2. **Elimination of t**:
   - Find rectangular form
   - Solve for relationship
   - Identify curve type
   - Check domain restrictions

### Derivatives
#### First Derivative
$\frac{dy}{dx} = \frac{\frac{dy}{dt}}{\frac{dx}{dt}}$

#### Process
1. **Find dy/dt and dx/dt**:
   - Differentiate y = g(t)
   - Differentiate x = f(t)
   - Keep in terms of t
   - Watch chain rule

2. **Form Quotient**:
   - Write fraction
   - Simplify if possible
   - Consider domain
   - Check undefined points

#### Example Walkthrough
Find dy/dx for x = t², y = t³
1. **Find derivatives**:
   - dx/dt = 2t
   - dy/dt = 3t²
2. **Form quotient**:
   - dy/dx = 3t²/2t
3. **Simplify**:
   - = 3t/2
   - = (3/2)x^(1/2)

### Second Derivative
$\frac{d^2y}{dx^2} = \frac{\frac{d}{dt}(\frac{dy}{dx})}{\frac{dx}{dt}}$

#### Process
1. **Find first derivative**
2. **Differentiate with respect to t**
3. **Divide by dx/dt**
4. **Simplify**

### Common Curves
#### Circle
- x = r cos t
- y = r sin t
- 0 ≤ t ≤ 2π
- Radius r

#### Cycloid
- x = r(t - sin t)
- y = r(1 - cos t)
- Rolling circle
- Period 2π

## 2. Polar Coordinates 🎯

### Understanding Polar Form
Points described by distance and angle. Think of it as:
- Distance from origin (r)
- Angle from x-axis (θ)
- Alternative to xy-coordinates
- Circular description

### Conversion Formulas
#### Polar to Rectangular
- x = r cos θ
- y = r sin θ
- r² = x² + y²
- θ = tan⁻¹(y/x)

#### Process
1. **Identify r and θ**
2. **Use conversion formulas**
3. **Simplify**
4. **Check quadrant**

### Common Polar Curves
#### Circle
- r = a (centered at origin)
- r = 2a cos θ (through origin)
- r = 2a sin θ (through origin)

#### Rose Curves
- r = a sin(nθ)
- n odd: n petals
- n even: 2n petals
- Symmetry about origin

#### Cardioid
- r = a(1 + cos θ)
- Heart-shaped
- One loop
- Size determined by a

### Area in Polar Form
$A = \frac{1}{2}\int_α^β r^2 dθ$

#### Process
1. **Identify bounds**:
   - Find full rotation
   - Consider symmetry
   - Check overlap
   - Verify angles

2. **Set up integral**:
   - Square r
   - Include 1/2
   - Use correct bounds
   - Watch for negative r

#### Example Walkthrough
Find area inside r = 2 cos θ
1. **Identify curve**:
   - Circle through origin
   - Radius = 1
2. **Find bounds**:
   - -π/2 to π/2
3. **Evaluate**:
   - $A = \frac{1}{2}\int_{-π/2}^{π/2} 4\cos^2 θ dθ$
   - = π

## 3. Vector Functions 🔄

### Understanding Vector Functions
Functions that output vectors. Think of it as:
- Position in space
- Motion path
- Component functions
- Parametric curve in space

### Basic Form
$\vec{r}(t) = \langle f(t), g(t), h(t) \rangle$

### Derivatives
#### Position Vector
$\vec{r}(t) = \langle x(t), y(t), z(t) \rangle$

#### Velocity Vector
$\vec{v}(t) = \vec{r}'(t) = \langle x'(t), y'(t), z'(t) \rangle$

#### Acceleration Vector
$\vec{a}(t) = \vec{r}''(t) = \langle x''(t), y''(t), z''(t) \rangle$

### Example Walkthrough
For $\vec{r}(t) = \langle t^2, t^3, t \rangle$, find velocity
1. **Differentiate components**:
   - x'(t) = 2t
   - y'(t) = 3t²
   - z'(t) = 1
2. **Write velocity**:
   - $\vec{v}(t) = \langle 2t, 3t^2, 1 \rangle$

## 4. Motion in Space 📈

### Understanding Motion
Describing position, velocity, and acceleration. Think of it as:
- Path through space
- Rate of position change
- Speed and direction
- Force and movement

### Key Concepts
#### Speed vs. Velocity
- Speed: $|\vec{v}(t)|$
- Velocity: $\vec{v}(t)$
- Direction matters
- Scalar vs. vector

#### TNB Frame
- Tangent vector
- Normal vector
- Binormal vector
- Orthogonal system

### Arc Length
$L = \int_a^b |\vec{r}'(t)|dt$

#### Process
1. **Find r'(t)**
2. **Calculate magnitude**
3. **Set up integral**
4. **Evaluate**

## 5. Applications 🎯

### Area Calculations
#### Polar Form
$A = \frac{1}{2}\int_α^β r^2dθ$

#### Parametric Form
$A = \int_a^b y\frac{dx}{dt}dt$

### Example Walkthrough
Find area inside r = 4 sin θ
1. **Identify curve**:
   - Circle through origin
   - Diameter = 4
2. **Set up integral**:
   - $A = \frac{1}{2}\int_0^π 16\sin^2 θ dθ$
3. **Evaluate**:
   - = 4π

## 📝 AP-Style Examples

### Example 1: Parametric Derivatives
Find dy/dx at t = 1 for x = t², y = t³

**Solution**:
1. **Find derivatives**:
   - dx/dt = 2t
   - dy/dt = 3t²
2. **Form quotient**:
   - dy/dx = 3t²/2t = 3t/2
3. **Evaluate at t = 1**:
   - dy/dx = 3/2

### Example 2: Polar Area
Find area inside r = 2 sin 2θ

**Solution**:
1. **Identify curve**:
   - Four-leaved rose
   - One leaf: 0 to π/4
2. **Set up integral**:
   - $A = 2\int_0^{π/4} 4\sin^2 2θ dθ$
3. **Evaluate**:
   - = 2

## 💡 Success Strategies

### 1. Curve Recognition
- Sketch curves
- Identify key points
- Consider symmetry
- Check period

### 2. Common Mistakes
- Wrong parameter range
- Sign errors
- Chain rule errors
- Domain restrictions

### 3. Calculator Tips
- Graph to verify
- Check endpoints
- Use parametric mode
- Confirm results

## 🔍 AP Exam Focus

### Free Response Tips
1. **Show work**:
   - Parameter elimination
   - Derivative calculations
   - Area/length setup
   - Vector operations

2. **Common Questions**:
   - Slope calculations
   - Area/arc length
   - Motion analysis
   - Curve sketching

### Multiple Choice Strategy
1. **Consider**:
   - Multiple approaches
   - Graphical insights
   - Parameter ranges
   - Symmetry

2. **Check**:
   - Units
   - Sign
   - Domain
   - Reasonableness

---

*💡 Pro Tip: Practice converting between parametric, polar, and rectangular forms - it's crucial for solving complex problems!* 