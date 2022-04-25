*{
    margin: 0;
    padding: 0;
}

.empty{height:622px;}

.container{
    margin:0 auto;
    padding-left:10px;
    padding-right:10px;
}

.flex-row{
    display: -webkit-flex;
	display: flex;
	-webkit-flex-direction: row;
	flex-direction: row;
}

.flex-wrap{
    display:flex;
    align-items: flex-start;
    flex-wrap: wrap;
}

.recent-block{
    margin-top:20px;
    max-width: 756px;
    border:1px solid #c4c4c4;
    padding:20px;
    border-radius: 6px;
}
.recent-block .title {
	-webkit-flex: auto;
	flex: auto;
}

.recent-block .pagination {
	width: 5rem;
    border:1px solid #CFCFCF;
    border-radius:5px;
}

.pagination svg{
    margin:auto;
}

.recent-block .body{
    margin:15px 0;
    justify-content:center;
}

.card{
    margin:auto;
    width:198px;
    height:128px;
    border-radius:6px;
    background: #FFFCFC;
    box-shadow: 0px 4px 16px rgba(0, 0, 0, 0.17);
}

.card .thumb{
    height:103px;
    background-color:#637B92;
    border-radius:6px;
}
.card .title{
    font-family: 'Montserrat', sans-serif;
    font-weight:600;
    font-size:13px;
    line-height: 15px;
    padding:5px 10px;
}


/* rensposible */


@media screen and (max-width:768px){
    .recent-block .body{
        justify-content: flex-start;
    }
    .card{margin:0 10px}
}

