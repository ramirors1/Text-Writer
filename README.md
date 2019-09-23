# Text-Writer
/**
 * TextWriter is a class that will store and display any text string.
 *
 * @author Ramiro
 * @version 1
 */
public class TextWriter {
    private String textToDisplay;

    public TextWriter() {
        textToDisplay = "";
    }

    public TextWriter(String inputText) {
        textToDisplay = inputText;
    }

    public void setTextToDisplay(String inputText) {
        textToDisplay = inputText;
    }

    public String getTextToDisplay() {
        return textToDisplay;
    }

    public void clearTextToDisplay() {
        textToDisplay = "";
    }
    public void display() {
        System.out.println(textToDisplay);
}
}

