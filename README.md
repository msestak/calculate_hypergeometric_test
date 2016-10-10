# NAME

calculate_hyper.R - R script to calculate log-odds, hypergeometric test, FDR and Bonferroni correction.

# SYNOPSIS

    # take input file,calculate hypergeometric test and write it all to output file
    ./calculate_hyper.R -i ./t/data/disease.txt -o ./t/data/disease_hyper.txt

# DESCRIPTION

This script requires input file in TabSeparated format with this header:

    phylostrata\tphylostrata_name\tFunctional term\tquant\tsample\thit\ttotal

after header paste your values like this:

    1\tCellular organisms\tdisease_genes\t970\t8285\t1760\t22845


it will then calculate log-odds, hypergeometric test, FDR and Bonferroni correction and write it to tsv file.

# CONFIGURATION

No configuration.

# AUTHOR

Copyright (C) <2016> <Martin Sebastijan Šestak> (<sestakm@yahoo.com>). All rights reserved.

# LICENSE

Copyright (C) Martin Sebastijan Šestak (<sestakm@yahoo.com>)

This program is free software; you can redistribute it and/or
modify it under the same terms as Perl itself. See L<perlartistic>.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. 

