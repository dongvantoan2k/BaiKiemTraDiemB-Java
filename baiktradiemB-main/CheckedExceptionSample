gói  Cuối cùng ;

nhập  java.io.IOException ;
nhập  java.nio.file.FileAlreadyExistsException ;
nhập  java.nio.file.Files ;
nhập  java.nio.file.Paths ;

public  class  CheckedExceptionSample {
	public  static  void  main ( String [] args ) ném  InterruptException {
		Chủ đề . ngủ ( 1000 );
		thử {
			Các tập tin . CreateFile ( Paths . nhận được ( " students.txt " ));
		} catch ( FileAlreadyExistsException e) {
			Hệ thống . ra ngoài . println ( " Đã có Tệp " );
			Hệ thống . ra ngoài . println (e . toString ());
		} catch ( IOException e) {
			e . printStackTrace ();
			Hệ thống . ra ngoài . println ( " mã lệnh: "  + e . toString ());
		} cuối cùng {
			Hệ thống . ra ngoài . println ( " Luôn được thực thi " );
		}
		Hệ thống . ra ngoài . println ( " Sau khi ngoại lệ " );
	}
}
