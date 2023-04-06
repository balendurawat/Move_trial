script {
    fun main() {
        let a: u8;
        a =10;

        let a: u64 = 10;

        let a = 10u128; 
    }
}



script {
    fun main() {
        let a: u8 = 10;
        let b = 100u64;

        if (a == (b as u)) abort 11;
        if ((a as u64) == b) abort 11;
    }
}


script {
    fun main() {
        // these are all the ways to do it
        let b : bool; b = true;
        let b : bool = true;
        let b = true;
        let b = false; // here's an example with false
    }
}


script {
    fun main() {
        let addr: address;

        addr = {{sender}};

        addr = 0x....;

        addr = wallet1...;
        
    }
}