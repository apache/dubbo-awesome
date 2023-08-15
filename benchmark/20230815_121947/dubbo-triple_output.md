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
# Warmup Iteration   1: 1.525 ops/ms
# Warmup Iteration   2: 3.372 ops/ms
# Warmup Iteration   3: 7.110 ops/ms
Iteration   1: 7.523 ops/ms
Iteration   2: 7.800 ops/ms
Iteration   3: 8.027 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.784 ±(99.9%) 4.602 ops/ms [Average]
  (min, avg, max) = (7.523, 7.784, 8.027), stdev = 0.252
  CI (99.9%): [3.182, 12.385] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.113 ops/ms
# Warmup Iteration   2: 6.462 ops/ms
# Warmup Iteration   3: 8.126 ops/ms
Iteration   1: 8.246 ops/ms
Iteration   2: 8.477 ops/ms
Iteration   3: 8.182 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.302 ±(99.9%) 2.837 ops/ms [Average]
  (min, avg, max) = (8.182, 8.302, 8.477), stdev = 0.156
  CI (99.9%): [5.465, 11.139] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.142 ops/ms
# Warmup Iteration   2: 6.512 ops/ms
# Warmup Iteration   3: 7.727 ops/ms
Iteration   1: 8.203 ops/ms
Iteration   2: 7.946 ops/ms
Iteration   3: 7.537 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.895 ±(99.9%) 6.132 ops/ms [Average]
  (min, avg, max) = (7.537, 7.895, 8.203), stdev = 0.336
  CI (99.9%): [1.764, 14.027] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.067 ops/ms
# Warmup Iteration   2: 5.318 ops/ms
# Warmup Iteration   3: 6.669 ops/ms
Iteration   1: 6.667 ops/ms
Iteration   2: 6.713 ops/ms
Iteration   3: 6.796 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.725 ±(99.9%) 1.193 ops/ms [Average]
  (min, avg, max) = (6.667, 6.725, 6.796), stdev = 0.065
  CI (99.9%): [5.533, 7.918] (assumes normal distribution)


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
# Warmup Iteration   1: 11.859 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.563 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.374 ±(99.9%) 0.007 ms/op
Iteration   1: 4.103 ±(99.9%) 0.006 ms/op
Iteration   2: 4.002 ±(99.9%) 0.010 ms/op
Iteration   3: 4.073 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.059 ±(99.9%) 0.938 ms/op [Average]
  (min, avg, max) = (4.002, 4.059, 4.103), stdev = 0.051
  CI (99.9%): [3.121, 4.997] (assumes normal distribution)


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
# Warmup Iteration   1: 11.089 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.626 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.866 ±(99.9%) 0.004 ms/op
Iteration   1: 3.826 ±(99.9%) 0.007 ms/op
Iteration   2: 3.985 ±(99.9%) 0.005 ms/op
Iteration   3: 3.956 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.922 ±(99.9%) 1.543 ms/op [Average]
  (min, avg, max) = (3.826, 3.922, 3.985), stdev = 0.085
  CI (99.9%): [2.379, 5.465] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 12.777 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.595 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.147 ±(99.9%) 0.008 ms/op
Iteration   1: 4.267 ±(99.9%) 0.004 ms/op
Iteration   2: 4.043 ±(99.9%) 0.008 ms/op
Iteration   3: 3.919 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.076 ±(99.9%) 3.210 ms/op [Average]
  (min, avg, max) = (3.919, 4.076, 4.267), stdev = 0.176
  CI (99.9%): [0.866, 7.286] (assumes normal distribution)


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
# Warmup Iteration   1: 14.323 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 5.332 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.876 ±(99.9%) 0.006 ms/op
Iteration   1: 4.800 ±(99.9%) 0.008 ms/op
Iteration   2: 4.720 ±(99.9%) 0.015 ms/op
Iteration   3: 4.566 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.695 ±(99.9%) 2.172 ms/op [Average]
  (min, avg, max) = (4.566, 4.695, 4.800), stdev = 0.119
  CI (99.9%): [2.523, 6.867] (assumes normal distribution)


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
# Warmup Iteration   1: 13.344 ±(99.9%) 0.202 ms/op
# Warmup Iteration   2: 5.195 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.506 ±(99.9%) 0.019 ms/op
Iteration   1: 4.140 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.921 ms/op
                 createUser·p0.50:   3.944 ms/op
                 createUser·p0.90:   4.940 ms/op
                 createUser·p0.95:   5.612 ms/op
                 createUser·p0.99:   7.864 ms/op
                 createUser·p0.999:  10.662 ms/op
                 createUser·p0.9999: 26.977 ms/op
                 createUser·p1.00:   27.656 ms/op

Iteration   2: 3.852 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   2.232 ms/op
                 createUser·p0.50:   3.744 ms/op
                 createUser·p0.90:   4.166 ms/op
                 createUser·p0.95:   4.506 ms/op
                 createUser·p0.99:   6.552 ms/op
                 createUser·p0.999:  26.247 ms/op
                 createUser·p0.9999: 31.578 ms/op
                 createUser·p1.00:   32.473 ms/op

Iteration   3: 3.937 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.292 ms/op
                 createUser·p0.50:   3.727 ms/op
                 createUser·p0.90:   4.456 ms/op
                 createUser·p0.95:   4.866 ms/op
                 createUser·p0.99:   7.102 ms/op
                 createUser·p0.999:  26.594 ms/op
                 createUser·p0.9999: 35.455 ms/op
                 createUser·p1.00:   36.372 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 241451
  mean =      3.973 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 259 
    [ 2.500,  5.000) = 228666 
    [ 5.000,  7.500) = 10319 
    [ 7.500, 10.000) = 1648 
    [10.000, 12.500) = 213 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 113 
    [27.500, 30.000) = 77 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.292 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      5.030 ms/op
     p(99.0000) =      7.315 ms/op
     p(99.9000) =     24.659 ms/op
     p(99.9900) =     33.686 ms/op
     p(99.9990) =     36.214 ms/op
     p(99.9999) =     36.372 ms/op
    p(100.0000) =     36.372 ms/op


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
# Warmup Iteration   1: 11.963 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 4.923 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 3.977 ±(99.9%) 0.013 ms/op
Iteration   1: 3.845 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.419 ms/op
                 existUser·p0.50:   3.682 ms/op
                 existUser·p0.90:   4.301 ms/op
                 existUser·p0.95:   4.940 ms/op
                 existUser·p0.99:   7.285 ms/op
                 existUser·p0.999:  19.988 ms/op
                 existUser·p0.9999: 23.091 ms/op
                 existUser·p1.00:   23.986 ms/op

Iteration   2: 3.767 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.409 ms/op
                 existUser·p0.50:   3.686 ms/op
                 existUser·p0.90:   4.108 ms/op
                 existUser·p0.95:   4.596 ms/op
                 existUser·p0.99:   7.184 ms/op
                 existUser·p0.999:  11.525 ms/op
                 existUser·p0.9999: 25.086 ms/op
                 existUser·p1.00:   25.854 ms/op

Iteration   3: 3.917 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.653 ms/op
                 existUser·p0.50:   3.674 ms/op
                 existUser·p0.90:   4.604 ms/op
                 existUser·p0.95:   5.325 ms/op
                 existUser·p0.99:   7.958 ms/op
                 existUser·p0.999:  11.370 ms/op
                 existUser·p0.9999: 36.372 ms/op
                 existUser·p1.00:   36.635 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 249710
  mean =      3.842 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 592 
    [ 2.500,  5.000) = 236802 
    [ 5.000,  7.500) = 9484 
    [ 7.500, 10.000) = 2201 
    [10.000, 12.500) = 394 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.409 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      7.635 ms/op
     p(99.9000) =     11.780 ms/op
     p(99.9900) =     31.888 ms/op
     p(99.9990) =     36.537 ms/op
     p(99.9999) =     36.635 ms/op
    p(100.0000) =     36.635 ms/op


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
# Warmup Iteration   1: 12.051 ±(99.9%) 0.178 ms/op
# Warmup Iteration   2: 4.963 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.167 ±(99.9%) 0.014 ms/op
Iteration   1: 4.104 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.159 ms/op
                 getUser·p0.50:   3.850 ms/op
                 getUser·p0.90:   4.858 ms/op
                 getUser·p0.95:   5.693 ms/op
                 getUser·p0.99:   8.552 ms/op
                 getUser·p0.999:  25.821 ms/op
                 getUser·p0.9999: 30.054 ms/op
                 getUser·p1.00:   30.638 ms/op

Iteration   2: 3.924 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.999 ms/op
                 getUser·p0.50:   3.740 ms/op
                 getUser·p0.90:   4.309 ms/op
                 getUser·p0.95:   4.981 ms/op
                 getUser·p0.99:   7.954 ms/op
                 getUser·p0.999:  11.903 ms/op
                 getUser·p0.9999: 28.302 ms/op
                 getUser·p1.00:   28.803 ms/op

Iteration   3: 4.062 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.339 ms/op
                 getUser·p0.50:   3.891 ms/op
                 getUser·p0.90:   4.678 ms/op
                 getUser·p0.95:   5.079 ms/op
                 getUser·p0.99:   7.365 ms/op
                 getUser·p0.999:  28.285 ms/op
                 getUser·p0.9999: 32.444 ms/op
                 getUser·p1.00:   32.834 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 238427
  mean =      4.029 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 114 
    [ 2.500,  5.000) = 223091 
    [ 5.000,  7.500) = 12034 
    [ 7.500, 10.000) = 2237 
    [10.000, 12.500) = 516 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 87 
    [27.500, 30.000) = 118 
    [30.000, 32.500) = 45 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.339 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.366 ms/op
     p(99.0000) =      8.036 ms/op
     p(99.9000) =     25.662 ms/op
     p(99.9900) =     31.926 ms/op
     p(99.9990) =     32.771 ms/op
     p(99.9999) =     32.834 ms/op
    p(100.0000) =     32.834 ms/op


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
# Warmup Iteration   1: 14.258 ±(99.9%) 0.213 ms/op
# Warmup Iteration   2: 5.398 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.992 ±(99.9%) 0.018 ms/op
Iteration   1: 4.853 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.876 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.333 ms/op
                 listUser·p0.95:   6.341 ms/op
                 listUser·p0.99:   9.423 ms/op
                 listUser·p0.999:  27.197 ms/op
                 listUser·p0.9999: 30.501 ms/op
                 listUser·p1.00:   35.848 ms/op

Iteration   2: 4.671 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.560 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.980 ms/op
                 listUser·p0.99:   8.734 ms/op
                 listUser·p0.999:  16.433 ms/op
                 listUser·p0.9999: 20.125 ms/op
                 listUser·p1.00:   20.775 ms/op

Iteration   3: 4.789 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.626 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.292 ms/op
                 listUser·p0.95:   6.758 ms/op
                 listUser·p0.99:   9.552 ms/op
                 listUser·p0.999:  16.941 ms/op
                 listUser·p0.9999: 19.649 ms/op
                 listUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 201214
  mean =      4.770 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 168196 
    [ 5.000,  7.500) = 26598 
    [ 7.500, 10.000) = 4903 
    [10.000, 12.500) = 853 
    [12.500, 15.000) = 221 
    [15.000, 17.500) = 203 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.876 ms/op
     p(50.0000) =      4.522 ms/op
     p(90.0000) =      5.276 ms/op
     p(95.0000) =      6.275 ms/op
     p(99.0000) =      9.339 ms/op
     p(99.9000) =     18.277 ms/op
     p(99.9900) =     29.582 ms/op
     p(99.9990) =     32.899 ms/op
     p(99.9999) =     35.848 ms/op
    p(100.0000) =     35.848 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.784 ± 4.602  ops/ms
ClientPb.existUser                       thrpt       3   8.302 ± 2.837  ops/ms
ClientPb.getUser                         thrpt       3   7.895 ± 6.132  ops/ms
ClientPb.listUser                        thrpt       3   6.725 ± 1.193  ops/ms
ClientPb.createUser                       avgt       3   4.059 ± 0.938   ms/op
ClientPb.existUser                        avgt       3   3.922 ± 1.543   ms/op
ClientPb.getUser                          avgt       3   4.076 ± 3.210   ms/op
ClientPb.listUser                         avgt       3   4.695 ± 2.172   ms/op
ClientPb.createUser                     sample  241451   3.973 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.292           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.789           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.563           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.030           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.315           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.659           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.686           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.372           ms/op
ClientPb.existUser                      sample  249710   3.842 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.409           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.682           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.325           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.989           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.635           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.780           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.888           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.635           ms/op
ClientPb.getUser                        sample  238427   4.029 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.339           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.826           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.637           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.366           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.036           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.662           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.926           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.834           ms/op
ClientPb.listUser                       sample  201214   4.770 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.876           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.276           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.275           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.339           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.277           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.582           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.848           ms/op
