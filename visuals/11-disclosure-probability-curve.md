# Disclosure Probability Curve - P(D) = 1 - e^(-lambda*t)

## Description
A mathematical visualization of the paper's formal disclosure probability function. The curve shows that the probability of data disclosure approaches certainty (1.0) asymptotically as time connected to power increases. This formalizes the paper's argument that privacy is not a stable state but a temporary condition with a mathematically predictable decay rate. Supports the formal framework in the paper's analytical section.

## Placement
Section 8 or Formal Framework section - alongside the mathematical formalization of the disclosure probability function.

## Gemini Image Generation Prompt
Render in a glassmorphism aesthetic throughout: use frosted glass panels with backdrop blur effects, semi-transparent layers with visible depth, subtle light borders that catch highlights, soft diffused shadows behind panels, and a layered floating composition with elements at different depth planes. Use translucent fills rather than solid colors for all major surfaces.

A clean, precise mathematical graph on a dark background (#111827) showing the exponential disclosure probability curve. The plot area, equation display, and annotation boxes should be rendered as frosted glass panels with translucent fills, backdrop blur, and subtle luminous borders:

MAIN PLOT:
X-axis: labeled "t (Time Connected to Power)" ranging from 0 to 10, with gridlines at each integer. The axis represents duration of data retention multiplied by institutional access.

Y-axis: labeled "P(D) - Probability of Data Disclosure" ranging from 0.0 to 1.0, with gridlines at 0.1 intervals.

Plot the curve P(D) = 1 - e^(-lambda*t) for lambda = 0.5, showing a smooth exponential approach curve that:
- Starts at P(D) = 0 when t = 0
- Rises steeply in the early period
- Gradually flattens as it approaches 1.0
- Never quite reaches 1.0 (asymptotic)

The curve itself should be drawn as a thick, smooth line in bright cyan (#06b6d4).

Add a horizontal dashed line at P(D) = 1.0 in red (#ef4444), labeled "Certainty (asymptote)." The curve approaches but never touches this line.

Add three annotated points on the curve:
- At t=1: P(D) approximately 0.39. Label: "Short-term storage. Moderate risk."
- At t=3: P(D) approximately 0.78. Label: "Medium-term. High probability."
- At t=7: P(D) approximately 0.97. Label: "Long-term retention. Near certainty."

Add a shaded region between the curve and the certainty line, colored in semi-transparent red, labeled "Residual uncertainty (diminishing)."

Add a shaded region below the curve, colored in semi-transparent cyan, labeled "Cumulative disclosure probability."

EQUATION DISPLAY:
In the upper-left corner, display the formula in clean mathematical notation:
P(D) = 1 - e^(-lambda * t)
Where:
- lambda = institutional access coefficient
- t = time connected to power
- P(D) = probability of data disclosure

Below the formula: "As t approaches infinity, P(D) approaches 1. Data connected to power will eventually be disclosed. Privacy is a temporary state, not a permanent condition."

SECONDARY ELEMENT:
Below the main plot, add a small comparison showing three curves with different lambda values (0.3, 0.5, 0.8) to show how higher institutional access (higher lambda) accelerates the approach to certainty. Label: "Higher lambda (more access points) = faster approach to disclosure certainty."

Style: Glassmorphism academic chart with frosted glass panels for the plot area and annotation boxes, translucent fills, backdrop blur, subtle luminous borders, and floating depth composition. Precise gridlines. Mathematical notation. Dark theme. Looks like it belongs in a peer-reviewed journal.

## Specifications
- Dimensions: 1200 x 900 pixels (landscape)
- Style: Glassmorphism - mathematical graph, academic, precise with frosted glass panels, translucent fills, backdrop blur, and floating depth composition
- Color Palette: Dark background (#111827), cyan curve (#06b6d4), red asymptote (#ef4444), grid lines (#1f2937), white text and labels (#e5e7eb), secondary curves in muted colors (#6366f1, #8b5cf6)
- Format: PNG
- Notes: Mathematical precision is critical. The curve must accurately represent the exponential CDF function. The annotation points should be mathematically correct for lambda=0.5. This visual formalizes the paper's central claim into a mathematical statement: privacy decay is not a risk but a mathematical certainty given sufficient time and access.
- Glassmorphism Rendering: The plot area should be a frosted glass panel with backdrop blur. Annotation callout boxes should be frosted glass cards floating at different depth planes with soft diffused shadows. The equation display box should also be frosted glass. The shaded regions under and above the curve should use translucent fills. Borders should be subtle and luminous.
