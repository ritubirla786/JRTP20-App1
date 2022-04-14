package in.ashokit.security;

import java.util.Base64;
import java.util.Base64.Decoder;
import java.util.Base64.Encoder;

public class PasswordService {

    int i=10;
    int b=20;
	public static String encode(String txt) {
		// making changes for BUD-101
    int x=10;
    int y=20;
		Encoder encoder=Base64.getEncoder();
		return encoder.encodeToString(txt.getBytes());
		
	}
	public static String decode(String encodeTxt) {
		// changes gor bud-121
		String s= "raju";
		Decoder decoder=Base64.getDecoder();
		byte[] decode=decoder.decode(encodeTxt);
		return new String(decode);
		
	}
	public static void main(String[] args) {
		String encode=PasswordService.encode("ashokit");
		System.out.println(encode);
	
	     String decode =PasswordService.decode(encode);
	     System.out.println(decode);
	
	}
	
}
