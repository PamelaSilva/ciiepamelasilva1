# ciiepamelasilva1
/

class Usuarios {
    public $id;
    public $nombre;
    public $apellidos;
    public $email;
    public $constrasena;
    
    //Metodos de acceso y modificacion
    //ID
    public function getId(){
        return $this->id;
    }
    public function setId($sId){    /*sId por SetId y asi sucesivamente*/
        $this->id = $sId;
    }
    
    //Nombre
    public function getNombre(){
        return $this->nombre;
    }
    public function setNombre($sNombre){
        $this->nombre = $sNombre;
    }
    
    //Apellidos
    public function getApellidos(){
        return $this->apellidos;
    }
    public function setApellidos($sApellidos){
        $this->apellidos = $sApellidos;
    }
    
    //Email
    public function getEmail(){
        return $this->email;
    }
    public function setEmail($sEmail){
        $this->email = $sEmail;
    }
    
    //Contraseña
    public function getContrasena(){
        return $this->contrasena;
    }
    public function setContrasena($sContrasena){
        $this->contrasena = $sContrasena;
    }
}
