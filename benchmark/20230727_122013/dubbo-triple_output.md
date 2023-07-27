# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.451 ops/ms
# Warmup Iteration   2: 3.575 ops/ms
# Warmup Iteration   3: 7.268 ops/ms
Iteration   1: 7.463 ops/ms
Iteration   2: 8.010 ops/ms
Iteration   3: 7.690 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.721 ±(99.9%) 5.013 ops/ms [Average]
  (min, avg, max) = (7.463, 7.721, 8.010), stdev = 0.275
  CI (99.9%): [2.707, 12.734] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.425 ops/ms
# Warmup Iteration   2: 6.875 ops/ms
# Warmup Iteration   3: 8.107 ops/ms
Iteration   1: 8.406 ops/ms
Iteration   2: 8.400 ops/ms
Iteration   3: 8.422 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.409 ±(99.9%) 0.207 ops/ms [Average]
  (min, avg, max) = (8.400, 8.409, 8.422), stdev = 0.011
  CI (99.9%): [8.203, 8.616] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.397 ops/ms
# Warmup Iteration   2: 6.517 ops/ms
# Warmup Iteration   3: 7.851 ops/ms
Iteration   1: 8.117 ops/ms
Iteration   2: 8.003 ops/ms
Iteration   3: 8.223 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.114 ±(99.9%) 2.015 ops/ms [Average]
  (min, avg, max) = (8.003, 8.114, 8.223), stdev = 0.110
  CI (99.9%): [6.099, 10.129] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.092 ops/ms
# Warmup Iteration   2: 5.906 ops/ms
# Warmup Iteration   3: 6.833 ops/ms
Iteration   1: 6.668 ops/ms
Iteration   2: 6.787 ops/ms
Iteration   3: 6.820 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.758 ±(99.9%) 1.466 ops/ms [Average]
  (min, avg, max) = (6.668, 6.758, 6.820), stdev = 0.080
  CI (99.9%): [5.293, 8.224] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 13.473 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 5.293 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.219 ±(99.9%) 0.012 ms/op
Iteration   1: 4.071 ±(99.9%) 0.006 ms/op
Iteration   2: 4.146 ±(99.9%) 0.004 ms/op
Iteration   3: 3.980 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.066 ±(99.9%) 1.520 ms/op [Average]
  (min, avg, max) = (3.980, 4.066, 4.146), stdev = 0.083
  CI (99.9%): [2.545, 5.586] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 12.827 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.724 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.204 ±(99.9%) 0.004 ms/op
Iteration   1: 4.074 ±(99.9%) 0.005 ms/op
Iteration   2: 3.808 ±(99.9%) 0.013 ms/op
Iteration   3: 3.951 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.944 ±(99.9%) 2.434 ms/op [Average]
  (min, avg, max) = (3.808, 3.944, 4.074), stdev = 0.133
  CI (99.9%): [1.510, 6.378] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 12.506 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.589 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.278 ±(99.9%) 0.005 ms/op
Iteration   1: 4.034 ±(99.9%) 0.010 ms/op
Iteration   2: 4.044 ±(99.9%) 0.008 ms/op
Iteration   3: 4.080 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.052 ±(99.9%) 0.440 ms/op [Average]
  (min, avg, max) = (4.034, 4.052, 4.080), stdev = 0.024
  CI (99.9%): [3.612, 4.493] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 16.203 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 5.851 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.747 ±(99.9%) 0.010 ms/op
Iteration   1: 4.740 ±(99.9%) 0.012 ms/op
Iteration   2: 4.795 ±(99.9%) 0.010 ms/op
Iteration   3: 4.859 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.798 ±(99.9%) 1.090 ms/op [Average]
  (min, avg, max) = (4.740, 4.798, 4.859), stdev = 0.060
  CI (99.9%): [3.708, 5.888] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 14.057 ±(99.9%) 0.204 ms/op
# Warmup Iteration   2: 5.550 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 4.342 ±(99.9%) 0.019 ms/op
Iteration   1: 4.149 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.808 ms/op
                 createUser·p0.50:   3.944 ms/op
                 createUser·p0.90:   4.899 ms/op
                 createUser·p0.95:   5.448 ms/op
                 createUser·p0.99:   7.905 ms/op
                 createUser·p0.999:  14.351 ms/op
                 createUser·p0.9999: 28.148 ms/op
                 createUser·p1.00:   29.327 ms/op

Iteration   2: 3.952 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.780 ms/op
                 createUser·p0.50:   3.813 ms/op
                 createUser·p0.90:   4.628 ms/op
                 createUser·p0.95:   5.058 ms/op
                 createUser·p0.99:   6.587 ms/op
                 createUser·p0.999:  17.302 ms/op
                 createUser·p0.9999: 27.804 ms/op
                 createUser·p1.00:   29.065 ms/op

Iteration   3: 4.018 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.587 ms/op
                 createUser·p0.50:   3.781 ms/op
                 createUser·p0.90:   4.653 ms/op
                 createUser·p0.95:   5.169 ms/op
                 createUser·p0.99:   6.906 ms/op
                 createUser·p0.999:  27.242 ms/op
                 createUser·p0.9999: 32.387 ms/op
                 createUser·p1.00:   33.620 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 237730
  mean =      4.038 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 236 
    [ 2.500,  5.000) = 221572 
    [ 5.000,  7.500) = 13799 
    [ 7.500, 10.000) = 1375 
    [10.000, 12.500) = 345 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 117 
    [27.500, 30.000) = 67 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.587 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.743 ms/op
     p(95.0000) =      5.226 ms/op
     p(99.0000) =      7.250 ms/op
     p(99.9000) =     24.445 ms/op
     p(99.9900) =     30.227 ms/op
     p(99.9990) =     33.358 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.329 ±(99.9%) 0.175 ms/op
# Warmup Iteration   2: 4.491 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.832 ±(99.9%) 0.009 ms/op
Iteration   1: 3.848 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.784 ms/op
                 existUser·p0.50:   3.756 ms/op
                 existUser·p0.90:   4.080 ms/op
                 existUser·p0.95:   4.481 ms/op
                 existUser·p0.99:   6.701 ms/op
                 existUser·p0.999:  23.030 ms/op
                 existUser·p0.9999: 26.173 ms/op
                 existUser·p1.00:   26.739 ms/op

Iteration   2: 3.897 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.880 ms/op
                 existUser·p0.50:   3.789 ms/op
                 existUser·p0.90:   4.284 ms/op
                 existUser·p0.95:   4.604 ms/op
                 existUser·p0.99:   6.840 ms/op
                 existUser·p0.999:  14.762 ms/op
                 existUser·p0.9999: 26.856 ms/op
                 existUser·p1.00:   28.213 ms/op

Iteration   3: 3.827 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.509 ms/op
                 existUser·p0.50:   3.707 ms/op
                 existUser·p0.90:   4.174 ms/op
                 existUser·p0.95:   4.424 ms/op
                 existUser·p0.99:   6.259 ms/op
                 existUser·p0.999:  26.203 ms/op
                 existUser·p0.9999: 29.283 ms/op
                 existUser·p1.00:   30.278 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 248826
  mean =      3.857 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 204 
    [ 2.500,  5.000) = 241351 
    [ 5.000,  7.500) = 5864 
    [ 7.500, 10.000) = 736 
    [10.000, 12.500) = 261 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 127 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.509 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      6.586 ms/op
     p(99.9000) =     22.839 ms/op
     p(99.9900) =     28.483 ms/op
     p(99.9990) =     29.689 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.150 ±(99.9%) 0.159 ms/op
# Warmup Iteration   2: 4.483 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.167 ±(99.9%) 0.013 ms/op
Iteration   1: 4.202 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.372 ms/op
                 getUser·p0.50:   3.953 ms/op
                 getUser·p0.90:   4.866 ms/op
                 getUser·p0.95:   6.300 ms/op
                 getUser·p0.99:   9.306 ms/op
                 getUser·p0.999:  13.778 ms/op
                 getUser·p0.9999: 27.091 ms/op
                 getUser·p1.00:   28.213 ms/op

Iteration   2: 4.014 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.761 ms/op
                 getUser·p0.50:   3.891 ms/op
                 getUser·p0.90:   4.407 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   6.914 ms/op
                 getUser·p0.999:  25.274 ms/op
                 getUser·p0.9999: 27.755 ms/op
                 getUser·p1.00:   29.393 ms/op

Iteration   3: 4.118 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.133 ms/op
                 getUser·p0.50:   4.006 ms/op
                 getUser·p0.90:   4.669 ms/op
                 getUser·p0.95:   5.145 ms/op
                 getUser·p0.99:   7.422 ms/op
                 getUser·p0.999:  12.173 ms/op
                 getUser·p0.9999: 29.375 ms/op
                 getUser·p1.00:   30.867 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 233660
  mean =      4.110 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53 
    [ 2.500,  5.000) = 220110 
    [ 5.000,  7.500) = 10014 
    [ 7.500, 10.000) = 2583 
    [10.000, 12.500) = 533 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 136 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.133 ms/op
     p(50.0000) =      3.961 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      5.177 ms/op
     p(99.0000) =      8.258 ms/op
     p(99.9000) =     17.334 ms/op
     p(99.9900) =     27.948 ms/op
     p(99.9990) =     30.791 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.851 ±(99.9%) 0.226 ms/op
# Warmup Iteration   2: 5.986 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.999 ±(99.9%) 0.020 ms/op
Iteration   1: 4.885 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.528 ms/op
                 listUser·p0.50:   4.686 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   9.519 ms/op
                 listUser·p0.999:  27.121 ms/op
                 listUser·p0.9999: 30.162 ms/op
                 listUser·p1.00:   30.638 ms/op

Iteration   2: 4.787 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.384 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   6.038 ms/op
                 listUser·p0.99:   9.339 ms/op
                 listUser·p0.999:  20.065 ms/op
                 listUser·p0.9999: 26.061 ms/op
                 listUser·p1.00:   26.477 ms/op

Iteration   3: 4.640 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.466 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.333 ms/op
                 listUser·p0.99:   8.184 ms/op
                 listUser·p0.999:  17.405 ms/op
                 listUser·p0.9999: 19.530 ms/op
                 listUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 201123
  mean =      4.769 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 168958 
    [ 5.000,  7.500) = 27389 
    [ 7.500, 10.000) = 3445 
    [10.000, 12.500) = 679 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 228 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 87 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.528 ms/op
     p(50.0000) =      4.579 ms/op
     p(90.0000) =      5.202 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =      8.991 ms/op
     p(99.9000) =     19.821 ms/op
     p(99.9900) =     29.710 ms/op
     p(99.9990) =     30.376 ms/op
     p(99.9999) =     30.638 ms/op
    p(100.0000) =     30.638 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.721 ± 5.013  ops/ms
ClientPb.existUser                       thrpt       3   8.409 ± 0.207  ops/ms
ClientPb.getUser                         thrpt       3   8.114 ± 2.015  ops/ms
ClientPb.listUser                        thrpt       3   6.758 ± 1.466  ops/ms
ClientPb.createUser                       avgt       3   4.066 ± 1.520   ms/op
ClientPb.existUser                        avgt       3   3.944 ± 2.434   ms/op
ClientPb.getUser                          avgt       3   4.052 ± 0.440   ms/op
ClientPb.listUser                         avgt       3   4.798 ± 1.090   ms/op
ClientPb.createUser                     sample  237730   4.038 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.587           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.854           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.743           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.226           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.250           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.445           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.227           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.620           ms/op
ClientPb.existUser                      sample  248826   3.857 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.509           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.744           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.190           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.506           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.586           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.839           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.483           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.278           ms/op
ClientPb.getUser                        sample  233660   4.110 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.133           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.961           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.596           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.177           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.258           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.334           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.948           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.867           ms/op
ClientPb.listUser                       sample  201123   4.769 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.528           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.579           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.202           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.693           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.991           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.821           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.710           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.638           ms/op
