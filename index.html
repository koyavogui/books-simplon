<?php
    $db = new PDO('sqlite:database/sqldb.db');
    $books = $db->query("SELECT * FROM books");
    $book = $books->fetchAll(PDO::FETCH_OBJ);
    $db = null;
?>

<!DOCTYPE html>
<html lang="fr">
<head>
    <?php require 'include/head.php' ?>
    <title>Akwaba</title>
    <style>
        .auteur{
      
             
        }
    </style>
</head>
<body class="px-0">  
    <div class="container-fluid px-0">
        <header class="container-fluid bg-success mb-3" style="height :50px;"></header>

        <div class="container mb-5">
            <form class="d-flex">
                <input class="form-control mr-2" type="search" placeholder="Chercher un livre" aria-label="Search">
                <button class="btn btn-outline-success" type="submit">Rechercher</button>
            </form>
        </div>
        <section class="container-fluid">
            <section class="d-flex justify-content-start flex-wrap" id="books">
            <?php foreach ($book as $b) {?>
                <div class="d-sm-inline-flex p-2 card border-0  col-sm-4" style="height : px;">
                        <div class="d-flex">
                            <img src="image/book.png" alt="" class="img-fluid w-30" style="height : 45px;">
                            <div class="row">
                                <span class="ml-3"> <strong>Titre:</strong> <?php echo $b->titreLivre;?></span>
                                <span class="ml-3 auteur"> <strong>Auteur:</strong> <?php echo $b->auteurLivre;?></span>
                                <span class="ml-3 flex-fill"> <strong>Genre:</strong> <?php echo $b->genreLivre;?></span> 
                                <span class="d-flex">
                                    <span class="ml-3 flex-grow-1"> <strong>Niveau:</strong> <?php echo $b->niveaClassLivre;?></span> 
                                    <span data-toggle="collapse" data-target="#collapseExample<?php echo $b->numLivre;?>" aria-expanded="false" aria-controls="collapseExample" class="text-info  mr-3"><i class="fas fa-info-circle"></i></span>
                                </span>
                            <div class="container-fluid">
                            
                            <div class="collapse" id="collapseExample<?php echo $b->numLivre;?>">
                                <div class="card card-body border border-info d-flex flex-wrap p-1">
                                    <span class="ml-3"><small> <strong>Catégorie complémentaire:</strong> <?php echo $b->catLivre;?></small></span>
                                    <span class="ml-3"><small> <strong>Editeur:</strong> <?php echo $b->editeurLivre;?></small></span>
                                    <span class="ml-3">
                                        <?php
                                            if ( $b->motCleU != "") {
                                                echo'<span class="badge rounded-pill bg-dark">'.$b->motCleU.'</span>';
                                            }
                                        ?>
                                        <?php
                                            if ( $b->motCleD != "") {
                                                echo'<span class="badge rounded-pill bg-dark">'.$b->motCleD.'</span>';
                                            }
                                        ?>
                                        <?php
                                            if ( $b->motCleT != "") {
                                                echo'<span class="badge rounded-pill bg-dark">'.$b->motCleT.'</span>';
                                            }
                                        ?>
                                        <?php
                                            if ( $b->motCleQ != "") {
                                                echo'<span class="badge rounded-pill bg-dark">'.$b->motCleQ.'</span>';
                                            }
                                        ?>
                                        <?php
                                            if ( $b->motCleUC != "") {
                                                echo'<span class="badge rounded-pill bg-dark">'.$b->motCleUC.'</span>';
                                            }
                                        ?>
                                    </span>
                                </div>
                            </div>
                            </div>
                            </div>
                        </div>
                </div>
            <?php  }?>

            </section>
        </section>
    </div>
    <?php require 'include/script.php' ?>
</body>
</html>