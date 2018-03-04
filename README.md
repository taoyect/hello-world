# hello-world
my first repository
public double sqrt(double c) {
if(c < 0) return Double.NaN;
  double t = c;
  while(Math.abs(t - c / t) > 0.001)
    t = (t + c / t) / 2.0;
  return t;
}
