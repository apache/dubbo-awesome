# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.683 ops/ms
# Warmup Iteration   2: 11.677 ops/ms
# Warmup Iteration   3: 12.448 ops/ms
Iteration   1: 12.631 ops/ms
Iteration   2: 12.569 ops/ms
Iteration   3: 12.629 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.610 ±(99.9%) 0.647 ops/ms [Average]
  (min, avg, max) = (12.569, 12.610, 12.631), stdev = 0.035
  CI (99.9%): [11.962, 13.257] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.984 ops/ms
# Warmup Iteration   2: 12.843 ops/ms
# Warmup Iteration   3: 12.845 ops/ms
Iteration   1: 12.818 ops/ms
Iteration   2: 12.768 ops/ms
Iteration   3: 12.737 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.775 ±(99.9%) 0.746 ops/ms [Average]
  (min, avg, max) = (12.737, 12.775, 12.818), stdev = 0.041
  CI (99.9%): [12.029, 13.520] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.586 ops/ms
# Warmup Iteration   2: 12.118 ops/ms
# Warmup Iteration   3: 12.620 ops/ms
Iteration   1: 12.616 ops/ms
Iteration   2: 12.682 ops/ms
Iteration   3: 12.612 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.636 ±(99.9%) 0.715 ops/ms [Average]
  (min, avg, max) = (12.612, 12.636, 12.682), stdev = 0.039
  CI (99.9%): [11.922, 13.351] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.776 ops/ms
# Warmup Iteration   2: 10.400 ops/ms
# Warmup Iteration   3: 10.382 ops/ms
Iteration   1: 10.316 ops/ms
Iteration   2: 10.366 ops/ms
Iteration   3: 10.268 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.317 ±(99.9%) 0.889 ops/ms [Average]
  (min, avg, max) = (10.268, 10.317, 10.366), stdev = 0.049
  CI (99.9%): [9.428, 11.206] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.086 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.622 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.547 ±(99.9%) 0.003 ms/op
Iteration   1: 2.587 ±(99.9%) 0.005 ms/op
Iteration   2: 2.598 ±(99.9%) 0.004 ms/op
Iteration   3: 2.542 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.576 ±(99.9%) 0.536 ms/op [Average]
  (min, avg, max) = (2.542, 2.576, 2.598), stdev = 0.029
  CI (99.9%): [2.040, 3.112] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.798 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.459 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.004 ms/op
Iteration   1: 2.456 ±(99.9%) 0.004 ms/op
Iteration   2: 2.495 ±(99.9%) 0.004 ms/op
Iteration   3: 2.468 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.473 ±(99.9%) 0.361 ms/op [Average]
  (min, avg, max) = (2.456, 2.473, 2.495), stdev = 0.020
  CI (99.9%): [2.112, 2.834] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.777 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.548 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.531 ±(99.9%) 0.004 ms/op
Iteration   1: 2.522 ±(99.9%) 0.004 ms/op
Iteration   2: 2.506 ±(99.9%) 0.004 ms/op
Iteration   3: 2.515 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.514 ±(99.9%) 0.150 ms/op [Average]
  (min, avg, max) = (2.506, 2.514, 2.522), stdev = 0.008
  CI (99.9%): [2.364, 2.664] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.628 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.093 ±(99.9%) 0.005 ms/op
Iteration   1: 3.051 ±(99.9%) 0.006 ms/op
Iteration   2: 3.053 ±(99.9%) 0.005 ms/op
Iteration   3: 3.043 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.049 ±(99.9%) 0.092 ms/op [Average]
  (min, avg, max) = (3.043, 3.049, 3.053), stdev = 0.005
  CI (99.9%): [2.957, 3.141] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.484 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 2.669 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.588 ±(99.9%) 0.006 ms/op
Iteration   1: 2.556 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.116 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.752 ms/op
                 createUser·p0.999:  10.618 ms/op
                 createUser·p0.9999: 14.459 ms/op
                 createUser·p1.00:   15.385 ms/op

Iteration   2: 2.550 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.652 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   3.916 ms/op
                 createUser·p0.999:  9.393 ms/op
                 createUser·p0.9999: 14.056 ms/op
                 createUser·p1.00:   14.467 ms/op

Iteration   3: 2.537 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.994 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.749 ms/op
                 createUser·p0.999:  8.946 ms/op
                 createUser·p0.9999: 11.911 ms/op
                 createUser·p1.00:   13.418 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376413
  mean =      2.548 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 180366 
    [ 2.500,  3.750) = 191778 
    [ 3.750,  5.000) = 3379 
    [ 5.000,  6.250) = 343 
    [ 6.250,  7.500) = 70 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 100 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 97 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.652 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.809 ms/op
     p(99.9000) =      9.011 ms/op
     p(99.9900) =     14.080 ms/op
     p(99.9990) =     15.208 ms/op
     p(99.9999) =     15.385 ms/op
    p(100.0000) =     15.385 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.845 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.514 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.468 ±(99.9%) 0.005 ms/op
Iteration   1: 2.455 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.715 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.502 ms/op
                 existUser·p0.999:  6.214 ms/op
                 existUser·p0.9999: 14.762 ms/op
                 existUser·p1.00:   15.876 ms/op

Iteration   2: 2.481 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.856 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   4.080 ms/op
                 existUser·p0.999:  6.317 ms/op
                 existUser·p0.9999: 12.699 ms/op
                 existUser·p1.00:   13.451 ms/op

Iteration   3: 2.454 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.888 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.658 ms/op
                 existUser·p0.999:  9.437 ms/op
                 existUser·p0.9999: 12.452 ms/op
                 existUser·p1.00:   13.500 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389297
  mean =      2.463 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 191737 
    [ 2.500,  3.750) = 193680 
    [ 3.750,  5.000) = 2611 
    [ 5.000,  6.250) = 809 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 114 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.715 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.744 ms/op
     p(99.9000) =      7.376 ms/op
     p(99.9900) =     14.009 ms/op
     p(99.9990) =     15.221 ms/op
     p(99.9999) =     15.876 ms/op
    p(100.0000) =     15.876 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.823 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.595 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.539 ±(99.9%) 0.006 ms/op
Iteration   1: 2.513 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.951 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   4.059 ms/op
                 getUser·p0.999:  11.321 ms/op
                 getUser·p0.9999: 13.729 ms/op
                 getUser·p1.00:   14.189 ms/op

Iteration   2: 2.518 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.929 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.781 ms/op
                 getUser·p0.999:  5.400 ms/op
                 getUser·p0.9999: 13.648 ms/op
                 getUser·p1.00:   14.090 ms/op

Iteration   3: 2.517 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.820 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.797 ms/op
                 getUser·p0.999:  8.715 ms/op
                 getUser·p0.9999: 12.097 ms/op
                 getUser·p1.00:   12.894 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381234
  mean =      2.516 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 189321 
    [ 2.500,  3.750) = 187279 
    [ 3.750,  5.000) = 3678 
    [ 5.000,  6.250) = 530 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 43 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 109 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      3.858 ms/op
     p(99.9000) =      6.104 ms/op
     p(99.9900) =     13.582 ms/op
     p(99.9990) =     14.126 ms/op
     p(99.9999) =     14.189 ms/op
    p(100.0000) =     14.189 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.740 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.009 ms/op
Iteration   1: 3.020 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.949 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.397 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.685 ms/op
                 listUser·p0.9999: 11.696 ms/op
                 listUser·p1.00:   12.337 ms/op

Iteration   2: 3.015 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.035 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  9.453 ms/op
                 listUser·p0.9999: 12.199 ms/op
                 listUser·p1.00:   12.681 ms/op

Iteration   3: 3.014 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.012 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.239 ms/op
                 listUser·p0.9999: 12.543 ms/op
                 listUser·p1.00:   14.221 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318003
  mean =      3.016 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 116 
    [ 1.250,  2.500) = 89940 
    [ 2.500,  3.750) = 189128 
    [ 3.750,  5.000) = 32350 
    [ 5.000,  6.250) = 5157 
    [ 6.250,  7.500) = 636 
    [ 7.500,  8.750) = 187 
    [ 8.750, 10.000) = 268 
    [10.000, 11.250) = 131 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.949 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =      9.503 ms/op
     p(99.9900) =     12.095 ms/op
     p(99.9990) =     13.167 ms/op
     p(99.9999) =     14.221 ms/op
    p(100.0000) =     14.221 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.610 ± 0.647  ops/ms
ClientPb.existUser                       thrpt       3  12.775 ± 0.746  ops/ms
ClientPb.getUser                         thrpt       3  12.636 ± 0.715  ops/ms
ClientPb.listUser                        thrpt       3  10.317 ± 0.889  ops/ms
ClientPb.createUser                       avgt       3   2.576 ± 0.536   ms/op
ClientPb.existUser                        avgt       3   2.473 ± 0.361   ms/op
ClientPb.getUser                          avgt       3   2.514 ± 0.150   ms/op
ClientPb.listUser                         avgt       3   3.049 ± 0.092   ms/op
ClientPb.createUser                     sample  376413   2.548 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.652           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.613           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.809           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.011           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.080           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.385           ms/op
ClientPb.existUser                      sample  389297   2.463 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.715           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.535           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.744           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.376           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.009           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.876           ms/op
ClientPb.getUser                        sample  381234   2.516 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.820           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.515           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.203           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.858           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.104           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.582           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.189           ms/op
ClientPb.listUser                       sample  318003   3.016 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.949           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.505           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.503           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.095           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.221           ms/op
