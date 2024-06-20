# Line Codes for Communication Systems

   This repository provides implementations of various line coding techniques used in [communication systems](https://en.wikipedia.org/wiki/Communications_system#:~:text=A%20communications%20system%20or%20communication,to%20form%20an%20integrated%20whole.).Line coding is a process of converting [digital data](https://en.wikipedia.org/wiki/Digital_data#:~:text=Digital%20data%2C%20in%20information%20theory,a%20string%20of%20alphanumeric%20characters.) to [digital signals](https://en.wikipedia.org/wiki/Digital_signal).
   This repository is structured into three main categories: 'Bipolar', 'Polar', and 'Unipolar', each containing methods for 'Non-Return-to-Zero (NRZ)' and 'Return-to-Zero (RZ)' coding.


## Line Coding Techniques

   * [Bipolar Line Coding](Bipolar)

      1. Bipolar NRZ:
         - The signal level alternates between positive and negative values for successive 1s.
         - Zero level for 0s.
         - More efficient use of bandwidth compared to unipolar line coding.

      2. Bipolar RZ:
         - Similar to Bipolar NRZ but returns to zero between each bit.
         - Provides a clearer timing for synchronization but requires more bandwidth.


   * [Polar Line Coding](Polar)

      1. Polar NRZ:
         - Uses two levels of voltage, positive and negative, to represent binary 1 and 0.
         - Does not return to zero between bits, thus more bandwidth efficient.

      2. Polar RZ:
         - Similar to Polar NRZ but returns to zero between each bit.
         - Easier to synchronize but requires more bandwidth.


   * [Unipolar Line Coding](Unipolar)

      1. Unipolar NRZ:
         - Uses a single non-zero voltage level to represent binary 1.
         - Zero voltage level represents binary 0.
         - Simplest form of line coding but can have DC component issues.

      2. Unipolar RZ:
         - Similar to Unipolar NRZ but returns to zero between each bit.
         - Easier to synchronize but requires more bandwidth.

## Repository Structure

   The repository is organized into the following directories and files:

   - Bipolar

       - [Bipolar_RZ.ipynb:](Bipolar/Bipolar_RZ.ipynb) Implementation of Bipolar Return-to-Zero (RZ) line coding.
       - [Bipolar_NRZ.ipynb:](Bipolar/Bipolar_NRZ.ipynb) Implementation of Bipolar Non-Return-to-Zero (NRZ) line coding.


   - Polar

       - [Polar_RZ.ipynb:](Polar/Polar_RZ.ipynb) Implementation of Polar Return-to-Zero (RZ) line coding.
       - [Polar_NRZ.ipynb:](Polar/Polar_NRZ.ipynb) Implementation of Polar Non-Return-to-Zero (NRZ) line coding.


   - Unipolar

       - [UNPolar_RZ.ipynb:](Unipolar/UNPolar_RZ.ipynb.ipynb) Implementation of Unipolar Return-to-Zero (RZ) line coding.
       - [UNPolar_NRZ.ipynb:](Unipolar/UNPolar_NRZ.ipynb) Implementation of Unipolar Non-Return-to-Zero (NRZ) line coding.
    

## References

   * The concepts and explanations of the following article are used:


      * [Line Codes for Communication Systems - Original Paper](Line%20Codes%20for%20Communication%20Systems.pdf)


   * BOOK:

      * [Computer Network Tanenbaum](Computer%20Network%20Tanenbaum.pdf): This book has been used to teach the concepts of communication systems.


   * You can also refer to the following file to know the performance of each of the implemented methods:


      * [Line Coding](Line%20Coding.pdf)

## License

   This repository is licensed under the MIT License.
   See the [LICENSE](./LICENSE) file for more details.