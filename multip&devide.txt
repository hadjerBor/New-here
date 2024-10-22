// Multiplication class
class Multiplication extends Calculator {
    @Override
    double compute(double A, double B) {
        return A * B;
    }
}

// Division class
class Division extends Calculator {
    @Override
    double compute(double A, double B) {
        if (B == 0) {
            throw new ArithmeticException("Cannot divide by zero.");
        }
        return A / B;
    }
}