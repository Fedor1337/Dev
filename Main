package DevSoft;

import java.io.IOException;
import java.util.ArrayList;
import java.util.List;
import java.util.Scanner;


public class MaiN {
    public static void main(String[] args) throws IOException{
        System.out.println("Справочник");
        System.out.println("1 - добавить контакт");
        System.out.println("2 - показать контакты");
        System.out.println("3 - удалить контакт");
        Scanner ac = new Scanner(System.in);
        int s = ac.nextInt();
        if (s == 1) {
        ButtonAdd add = new ButtonAdd();
            add.Bad();
        }
        if (s == 2) {
        ButtonShow show = new ButtonShow();
            show.Button();
        }
        if (s == 3){
        ButtonClear clear = new ButtonClear();
            clear.Button();
        }
        if (s > 3) {
            System.out.println("Такой операции нет");
        }
        if (s < 1) {
            System.out.println("такой операции нет");
        }

    }
}
