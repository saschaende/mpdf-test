# MPDF speed test

Install with composer

    composer create-project saschaende/mpdf-test

Call the script from your terminal:

    php pdftest
    
The script will load the contents of style.css and lorem.text and build up to 100 pdf pages. While generating the pdf, you can get the actual page number with:

    // Get actual page
    echo "page: ".$mpdf->PageNo()."\n";
    
Script execution on MacBook Pro: 4.9377 seconds