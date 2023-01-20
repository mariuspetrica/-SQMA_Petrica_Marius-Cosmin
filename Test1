import org.junit.Test;
import static org.junit.Assert.assertEquals;

public class TestStringMethods {

    @Test
    public void testUpper() {
        String str = "foo";
        String result = str.toUpperCase();
        assertEquals("FOO", result);
    }

    @Test
    public void testIsUpper() {
        String str1 = "FOO";
        String str2 = "Foo";
        boolean result1 = str1.equals(str1.toUpperCase());
        boolean result2 = str2.equals(str2.toUpperCase());
        assertEquals(true, result1);
        assertEquals(false, result2);
    }
}
