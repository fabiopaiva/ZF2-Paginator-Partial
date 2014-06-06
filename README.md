ZF2-Paginator-Partial
=====================

#Install

    cd pathForYourApplicationView
    git clone https://github.com/fabiopaiva/ZF2-Paginator-Partial/ zf2-paginator-partial

#Usage

    <?php
        echo $this->paginationControl($myPaginator, 'Sliding', 'zf2-paginator-partial/paginator', array('route' => 'myRouteName'));
    ?>

