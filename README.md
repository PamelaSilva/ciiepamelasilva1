# ciiepamelasilva1
/

class Asiste_a_evento {
    public $id;
    public $usuario;
    public $evento;
    
    //Metodos de acceso y  modificacion
    //ID
    public function getId(){
        return $this->id;
    }
    public function setId($sId){
        $this->id = $sId;
    }
    
    //Usuario
    public function getUsuario(){
        return $this->usuario;
    }
    public function setUsuario($sUsuario){
        $this->usuario = $sUsuario;
    }
    
    //Evento
    public function getEvento(){
        return $this->evento;
    }
    public function setEvento($sEvento){
        $this->evento = $sEvento;
    }
}

?>
