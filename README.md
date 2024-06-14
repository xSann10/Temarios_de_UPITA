#include <iostream>
#include <string>
#include <fstream>

using namespace std;

// CLASE TAREA
class TAREA {
private:
    string Titulo;
    string Fecha;
    float Hora;
public:
    TAREA* prev;
    TAREA* next;

public:
    TAREA(const string& Titulo, const string& Fecha, float Hora, int )
        : Titulo(Titulo), Fecha(Fecha), Hora(Hora), {}

    // Getters y setters
    string getTitulo() const { return Titulo; }
    void setTitulo(const string& Titulo) { this->Titulo = Titulo; }
    string getFecha() const { return Fecha; }
    void setFecha(const string& Fecha) { this->Fecha = Fecha; }
    float getHora() const { return Hora; }
    void setHora(float Hora) { this->Hora = Hora; }
    int get() const { return ; }
    void set(int ) { this-> = ; }
};
