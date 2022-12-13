# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.218 ops/ms
# Warmup Iteration   2: 2.832 ops/ms
# Warmup Iteration   3: 5.678 ops/ms
Iteration   1: 5.952 ops/ms
Iteration   2: 6.385 ops/ms
Iteration   3: 6.107 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.148 ±(99.9%) 4.005 ops/ms [Average]
  (min, avg, max) = (5.952, 6.148, 6.385), stdev = 0.220
  CI (99.9%): [2.143, 10.153] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 1.959 ops/ms
# Warmup Iteration   2: 5.418 ops/ms
# Warmup Iteration   3: 6.294 ops/ms
Iteration   1: 6.502 ops/ms
Iteration   2: 6.596 ops/ms
Iteration   3: 6.300 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.466 ±(99.9%) 2.759 ops/ms [Average]
  (min, avg, max) = (6.300, 6.466, 6.596), stdev = 0.151
  CI (99.9%): [3.707, 9.225] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.672 ops/ms
# Warmup Iteration   2: 4.676 ops/ms
# Warmup Iteration   3: 5.935 ops/ms
Iteration   1: 5.871 ops/ms
Iteration   2: 5.840 ops/ms
Iteration   3: 5.868 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.860 ±(99.9%) 0.313 ops/ms [Average]
  (min, avg, max) = (5.840, 5.860, 5.871), stdev = 0.017
  CI (99.9%): [5.546, 6.173] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.496 ops/ms
# Warmup Iteration   2: 3.968 ops/ms
# Warmup Iteration   3: 5.232 ops/ms
Iteration   1: 5.244 ops/ms
Iteration   2: 5.493 ops/ms
Iteration   3: 5.040 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.259 ±(99.9%) 4.140 ops/ms [Average]
  (min, avg, max) = (5.040, 5.259, 5.493), stdev = 0.227
  CI (99.9%): [1.120, 9.399] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 17.938 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 6.104 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 5.551 ±(99.9%) 0.012 ms/op
Iteration   1: 5.143 ±(99.9%) 0.013 ms/op
Iteration   2: 5.255 ±(99.9%) 0.016 ms/op
Iteration   3: 5.162 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.187 ±(99.9%) 1.090 ms/op [Average]
  (min, avg, max) = (5.143, 5.187, 5.255), stdev = 0.060
  CI (99.9%): [4.097, 6.276] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 16.754 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 5.693 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.053 ±(99.9%) 0.007 ms/op
Iteration   1: 4.960 ±(99.9%) 0.009 ms/op
Iteration   2: 4.822 ±(99.9%) 0.021 ms/op
Iteration   3: 5.006 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.929 ±(99.9%) 1.748 ms/op [Average]
  (min, avg, max) = (4.822, 4.929, 5.006), stdev = 0.096
  CI (99.9%): [3.182, 6.677] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 16.235 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 6.722 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.343 ±(99.9%) 0.013 ms/op
Iteration   1: 5.297 ±(99.9%) 0.008 ms/op
Iteration   2: 4.981 ±(99.9%) 0.014 ms/op
Iteration   3: 5.203 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.160 ±(99.9%) 2.967 ms/op [Average]
  (min, avg, max) = (4.981, 5.160, 5.297), stdev = 0.163
  CI (99.9%): [2.193, 8.127] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 16.896 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 7.142 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 6.278 ±(99.9%) 0.015 ms/op
Iteration   1: 5.864 ±(99.9%) 0.012 ms/op
Iteration   2: 6.083 ±(99.9%) 0.011 ms/op
Iteration   3: 5.966 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.971 ±(99.9%) 2.005 ms/op [Average]
  (min, avg, max) = (5.864, 5.971, 6.083), stdev = 0.110
  CI (99.9%): [3.966, 7.976] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 14.063 ±(99.9%) 0.204 ms/op
# Warmup Iteration   2: 6.460 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.446 ±(99.9%) 0.020 ms/op
Iteration   1: 5.276 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.997 ms/op
                 createUser·p0.50:   4.973 ms/op
                 createUser·p0.90:   6.554 ms/op
                 createUser·p0.95:   7.635 ms/op
                 createUser·p0.99:   10.783 ms/op
                 createUser·p0.999:  23.759 ms/op
                 createUser·p0.9999: 31.804 ms/op
                 createUser·p1.00:   32.571 ms/op

Iteration   2: 5.210 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.146 ms/op
                 createUser·p0.50:   5.005 ms/op
                 createUser·p0.90:   6.193 ms/op
                 createUser·p0.95:   6.758 ms/op
                 createUser·p0.99:   10.256 ms/op
                 createUser·p0.999:  25.563 ms/op
                 createUser·p0.9999: 30.062 ms/op
                 createUser·p1.00:   31.326 ms/op

Iteration   3: 5.034 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.604 ms/op
                 createUser·p0.50:   4.882 ms/op
                 createUser·p0.90:   5.898 ms/op
                 createUser·p0.95:   6.341 ms/op
                 createUser·p0.99:   8.233 ms/op
                 createUser·p0.999:  26.527 ms/op
                 createUser·p0.9999: 29.557 ms/op
                 createUser·p1.00:   31.195 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 185514
  mean =      5.171 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 99142 
    [ 5.000,  7.500) = 80233 
    [ 7.500, 10.000) = 4300 
    [10.000, 12.500) = 979 
    [12.500, 15.000) = 365 
    [15.000, 17.500) = 192 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 65 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.604 ms/op
     p(50.0000) =      4.948 ms/op
     p(90.0000) =      6.185 ms/op
     p(95.0000) =      6.865 ms/op
     p(99.0000) =      9.896 ms/op
     p(99.9000) =     24.066 ms/op
     p(99.9900) =     30.110 ms/op
     p(99.9990) =     32.067 ms/op
     p(99.9999) =     32.571 ms/op
    p(100.0000) =     32.571 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 13.894 ±(99.9%) 0.213 ms/op
# Warmup Iteration   2: 5.426 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.894 ±(99.9%) 0.015 ms/op
Iteration   1: 5.126 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.923 ms/op
                 existUser·p0.50:   4.866 ms/op
                 existUser·p0.90:   6.267 ms/op
                 existUser·p0.95:   7.348 ms/op
                 existUser·p0.99:   9.765 ms/op
                 existUser·p0.999:  27.314 ms/op
                 existUser·p0.9999: 32.170 ms/op
                 existUser·p1.00:   33.554 ms/op

Iteration   2: 4.815 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.989 ms/op
                 existUser·p0.50:   4.645 ms/op
                 existUser·p0.90:   5.702 ms/op
                 existUser·p0.95:   6.275 ms/op
                 existUser·p0.99:   8.257 ms/op
                 existUser·p0.999:  15.132 ms/op
                 existUser·p0.9999: 28.368 ms/op
                 existUser·p1.00:   28.869 ms/op

Iteration   3: 4.745 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.999 ms/op
                 existUser·p0.50:   4.555 ms/op
                 existUser·p0.90:   5.587 ms/op
                 existUser·p0.95:   6.259 ms/op
                 existUser·p0.99:   8.380 ms/op
                 existUser·p0.999:  20.611 ms/op
                 existUser·p0.9999: 30.220 ms/op
                 existUser·p1.00:   30.933 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 196348
  mean =      4.889 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 97 
    [ 2.500,  5.000) = 135834 
    [ 5.000,  7.500) = 55073 
    [ 7.500, 10.000) = 4194 
    [10.000, 12.500) = 609 
    [12.500, 15.000) = 308 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 96 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.923 ms/op
     p(50.0000) =      4.669 ms/op
     p(90.0000) =      5.857 ms/op
     p(95.0000) =      6.570 ms/op
     p(99.0000) =      8.864 ms/op
     p(99.9000) =     20.611 ms/op
     p(99.9900) =     30.638 ms/op
     p(99.9990) =     32.607 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 16.653 ±(99.9%) 0.240 ms/op
# Warmup Iteration   2: 6.295 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.586 ±(99.9%) 0.023 ms/op
Iteration   1: 5.405 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.062 ms/op
                 getUser·p0.50:   5.202 ms/op
                 getUser·p0.90:   6.390 ms/op
                 getUser·p0.95:   7.070 ms/op
                 getUser·p0.99:   9.897 ms/op
                 getUser·p0.999:  24.220 ms/op
                 getUser·p0.9999: 28.578 ms/op
                 getUser·p1.00:   29.983 ms/op

Iteration   2: 5.621 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.565 ms/op
                 getUser·p0.50:   5.267 ms/op
                 getUser·p0.90:   7.119 ms/op
                 getUser·p0.95:   8.667 ms/op
                 getUser·p0.99:   11.403 ms/op
                 getUser·p0.999:  18.189 ms/op
                 getUser·p0.9999: 33.343 ms/op
                 getUser·p1.00:   35.652 ms/op

Iteration   3: 5.451 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.646 ms/op
                 getUser·p0.50:   5.145 ms/op
                 getUser·p0.90:   6.832 ms/op
                 getUser·p0.95:   7.782 ms/op
                 getUser·p0.99:   10.240 ms/op
                 getUser·p0.999:  25.215 ms/op
                 getUser·p0.9999: 30.990 ms/op
                 getUser·p1.00:   31.457 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 174959
  mean =      5.491 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 67153 
    [ 5.000,  7.500) = 96844 
    [ 7.500, 10.000) = 8526 
    [10.000, 12.500) = 1597 
    [12.500, 15.000) = 420 
    [15.000, 17.500) = 178 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.565 ms/op
     p(50.0000) =      5.210 ms/op
     p(90.0000) =      6.676 ms/op
     p(95.0000) =      7.913 ms/op
     p(99.0000) =     10.715 ms/op
     p(99.9000) =     21.038 ms/op
     p(99.9900) =     32.359 ms/op
     p(99.9990) =     34.055 ms/op
     p(99.9999) =     35.652 ms/op
    p(100.0000) =     35.652 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 18.646 ±(99.9%) 0.417 ms/op
# Warmup Iteration   2: 7.655 ±(99.9%) 0.054 ms/op
# Warmup Iteration   3: 6.324 ±(99.9%) 0.025 ms/op
Iteration   1: 6.312 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.560 ms/op
                 listUser·p0.50:   5.939 ms/op
                 listUser·p0.90:   7.545 ms/op
                 listUser·p0.95:   9.142 ms/op
                 listUser·p0.99:   12.517 ms/op
                 listUser·p0.999:  28.756 ms/op
                 listUser·p0.9999: 31.687 ms/op
                 listUser·p1.00:   36.700 ms/op

Iteration   2: 6.382 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.879 ms/op
                 listUser·p0.50:   6.054 ms/op
                 listUser·p0.90:   7.545 ms/op
                 listUser·p0.95:   8.618 ms/op
                 listUser·p0.99:   12.364 ms/op
                 listUser·p0.999:  29.688 ms/op
                 listUser·p0.9999: 32.273 ms/op
                 listUser·p1.00:   32.768 ms/op

Iteration   3: 6.132 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.810 ms/op
                 listUser·p0.50:   5.882 ms/op
                 listUser·p0.90:   7.127 ms/op
                 listUser·p0.95:   8.086 ms/op
                 listUser·p0.99:   10.732 ms/op
                 listUser·p0.999:  20.671 ms/op
                 listUser·p0.9999: 24.038 ms/op
                 listUser·p1.00:   25.592 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 153008
  mean =      6.274 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 7665 
    [ 5.000,  7.500) = 131204 
    [ 7.500, 10.000) = 10369 
    [10.000, 12.500) = 2506 
    [12.500, 15.000) = 637 
    [15.000, 17.500) = 263 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 43 
    [27.500, 30.000) = 102 
    [30.000, 32.500) = 58 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.560 ms/op
     p(50.0000) =      5.956 ms/op
     p(90.0000) =      7.397 ms/op
     p(95.0000) =      8.602 ms/op
     p(99.0000) =     12.091 ms/op
     p(99.9000) =     28.311 ms/op
     p(99.9900) =     31.788 ms/op
     p(99.9990) =     34.616 ms/op
     p(99.9999) =     36.700 ms/op
    p(100.0000) =     36.700 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.148 ± 4.005  ops/ms
ClientPb.existUser                       thrpt       3   6.466 ± 2.759  ops/ms
ClientPb.getUser                         thrpt       3   5.860 ± 0.313  ops/ms
ClientPb.listUser                        thrpt       3   5.259 ± 4.140  ops/ms
ClientPb.createUser                       avgt       3   5.187 ± 1.090   ms/op
ClientPb.existUser                        avgt       3   4.929 ± 1.748   ms/op
ClientPb.getUser                          avgt       3   5.160 ± 2.967   ms/op
ClientPb.listUser                         avgt       3   5.971 ± 2.005   ms/op
ClientPb.createUser                     sample  185514   5.171 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.604           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.948           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.185           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.865           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.896           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.066           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.110           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.571           ms/op
ClientPb.existUser                      sample  196348   4.889 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.923           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.669           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.857           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.570           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.864           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.611           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.638           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.554           ms/op
ClientPb.getUser                        sample  174959   5.491 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.565           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.210           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.676           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.913           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.715           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.038           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.359           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.652           ms/op
ClientPb.listUser                       sample  153008   6.274 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.560           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.956           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.397           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.602           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.091           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.311           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.788           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.700           ms/op
