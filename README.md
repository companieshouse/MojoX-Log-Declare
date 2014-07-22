# NAME

MojoX::Log::Declare - Integrate Log::Declare with Mojolicious

# SYNOPSIS

    use Mojo::Base 'Mojolicious';
    use MojoX::Log::Declare;

    sub startup {
       my $self = shift;

       $self->log( MojoX::Log::Declare->new() );
       # ...
    }
