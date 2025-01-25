#include <iostream>
#include <cmath>
using namespace std;

int main()
{
     int deter;
     float matrix[2][2];
     cout << "Enter numbers in the matrix in order of 11 12 21 22 " << endl;
     cin >> matrix[0][0] >> matrix[0][1] >> matrix[1][0] >> matrix[1][1];
     cout << "matrix is-\n";
     cout << "|" << matrix[0][0] << " " << matrix[0][1] << "|\n";
     cout << "|" << matrix[1][0] << " " << matrix[1][1] << "|\n";
     deter = matrix[0][0] * matrix[1][1] - matrix[0][1] * matrix[1][0];
     cout << "Determinant is " << deter << endl;

     float S1 = matrix[0][0] + matrix[1][1];
     cout << "S1 is " << S1 << endl;

     float eigenval1 = (S1 + sqrt(S1 * S1 - 4 * deter)) / 2;
     float eigenval2 = (S1 - sqrt(S1 * S1 - 4 * deter)) / 2;
     cout << "Eigenvalues are " << eigenval1 << " and " << eigenval2 << endl;

     float eigenvector1_x = 1;
     float eigenvector1_y = (eigenval1 - matrix[0][0]) / matrix[0][1];

     cout << "Eigenvector for eigenval1:\n";
     cout << "|" << eigenvector1_x << "|\n";
     cout << "|" << eigenvector1_y << "|\n";

     float eigenvector2_x = 1;
     float eigenvector2_y = (eigenval2 - matrix[0][0]) / matrix[0][1];

     cout << "Eigenvector for eigenval2:\n";
     cout << "|" << eigenvector2_x << "|\n";
     cout << "|" << eigenvector2_y << "|\n";

     return 0;
}
