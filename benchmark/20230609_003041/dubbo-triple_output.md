# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.634 ops/ms
# Warmup Iteration   2: 4.060 ops/ms
# Warmup Iteration   3: 6.844 ops/ms
Iteration   1: 7.071 ops/ms
Iteration   2: 7.593 ops/ms
Iteration   3: 7.277 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.314 ±(99.9%) 4.794 ops/ms [Average]
  (min, avg, max) = (7.071, 7.314, 7.593), stdev = 0.263
  CI (99.9%): [2.519, 12.108] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.640 ops/ms
# Warmup Iteration   2: 7.344 ops/ms
# Warmup Iteration   3: 7.570 ops/ms
Iteration   1: 8.074 ops/ms
Iteration   2: 8.062 ops/ms
Iteration   3: 7.645 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.927 ±(99.9%) 4.456 ops/ms [Average]
  (min, avg, max) = (7.645, 7.927, 8.074), stdev = 0.244
  CI (99.9%): [3.471, 12.383] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.239 ops/ms
# Warmup Iteration   2: 6.906 ops/ms
# Warmup Iteration   3: 7.460 ops/ms
Iteration   1: 7.288 ops/ms
Iteration   2: 7.521 ops/ms
Iteration   3: 7.293 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.367 ±(99.9%) 2.422 ops/ms [Average]
  (min, avg, max) = (7.288, 7.367, 7.521), stdev = 0.133
  CI (99.9%): [4.945, 9.789] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.324 ops/ms
# Warmup Iteration   2: 5.878 ops/ms
# Warmup Iteration   3: 6.191 ops/ms
Iteration   1: 6.367 ops/ms
Iteration   2: 6.227 ops/ms
Iteration   3: 6.454 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.349 ±(99.9%) 2.086 ops/ms [Average]
  (min, avg, max) = (6.227, 6.349, 6.454), stdev = 0.114
  CI (99.9%): [4.263, 8.435] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 11.356 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.781 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.400 ±(99.9%) 0.013 ms/op
Iteration   1: 4.417 ±(99.9%) 0.008 ms/op
Iteration   2: 4.345 ±(99.9%) 0.012 ms/op
Iteration   3: 4.284 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.349 ±(99.9%) 1.222 ms/op [Average]
  (min, avg, max) = (4.284, 4.349, 4.417), stdev = 0.067
  CI (99.9%): [3.127, 5.570] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 10.169 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.385 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.224 ±(99.9%) 0.008 ms/op
Iteration   1: 4.288 ±(99.9%) 0.008 ms/op
Iteration   2: 4.089 ±(99.9%) 0.006 ms/op
Iteration   3: 4.179 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.185 ±(99.9%) 1.811 ms/op [Average]
  (min, avg, max) = (4.089, 4.185, 4.288), stdev = 0.099
  CI (99.9%): [2.375, 5.996] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.757 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.782 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.339 ±(99.9%) 0.012 ms/op
Iteration   1: 4.277 ±(99.9%) 0.016 ms/op
Iteration   2: 4.331 ±(99.9%) 0.009 ms/op
Iteration   3: 4.382 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.330 ±(99.9%) 0.958 ms/op [Average]
  (min, avg, max) = (4.277, 4.330, 4.382), stdev = 0.053
  CI (99.9%): [3.372, 5.289] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 12.766 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 5.359 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.085 ±(99.9%) 0.013 ms/op
Iteration   1: 5.024 ±(99.9%) 0.017 ms/op
Iteration   2: 5.142 ±(99.9%) 0.013 ms/op
Iteration   3: 5.143 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.103 ±(99.9%) 1.247 ms/op [Average]
  (min, avg, max) = (5.024, 5.103, 5.143), stdev = 0.068
  CI (99.9%): [3.856, 6.350] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 12.006 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 5.045 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.686 ±(99.9%) 0.018 ms/op
Iteration   1: 4.471 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.935 ms/op
                 createUser·p0.50:   4.268 ms/op
                 createUser·p0.90:   5.448 ms/op
                 createUser·p0.95:   6.029 ms/op
                 createUser·p0.99:   8.069 ms/op
                 createUser·p0.999:  14.065 ms/op
                 createUser·p0.9999: 26.078 ms/op
                 createUser·p1.00:   26.575 ms/op

Iteration   2: 4.254 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.980 ms/op
                 createUser·p0.50:   4.092 ms/op
                 createUser·p0.90:   5.054 ms/op
                 createUser·p0.95:   5.505 ms/op
                 createUser·p0.99:   6.865 ms/op
                 createUser·p0.999:  22.998 ms/op
                 createUser·p0.9999: 26.672 ms/op
                 createUser·p1.00:   28.344 ms/op

Iteration   3: 4.514 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.943 ms/op
                 createUser·p0.50:   4.325 ms/op
                 createUser·p0.90:   5.431 ms/op
                 createUser·p0.95:   6.103 ms/op
                 createUser·p0.99:   8.136 ms/op
                 createUser·p0.999:  17.997 ms/op
                 createUser·p0.9999: 31.228 ms/op
                 createUser·p1.00:   31.490 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 217451
  mean =      4.410 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 276 
    [ 2.500,  5.000) = 181336 
    [ 5.000,  7.500) = 33300 
    [ 7.500, 10.000) = 1877 
    [10.000, 12.500) = 249 
    [12.500, 15.000) = 144 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 84 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.943 ms/op
     p(50.0000) =      4.211 ms/op
     p(90.0000) =      5.325 ms/op
     p(95.0000) =      5.874 ms/op
     p(99.0000) =      7.733 ms/op
     p(99.9000) =     21.288 ms/op
     p(99.9900) =     29.229 ms/op
     p(99.9990) =     31.419 ms/op
     p(99.9999) =     31.490 ms/op
    p(100.0000) =     31.490 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 11.919 ±(99.9%) 0.184 ms/op
# Warmup Iteration   2: 4.535 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.137 ±(99.9%) 0.012 ms/op
Iteration   1: 4.221 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.845 ms/op
                 existUser·p0.50:   4.067 ms/op
                 existUser·p0.90:   5.038 ms/op
                 existUser·p0.95:   5.587 ms/op
                 existUser·p0.99:   7.551 ms/op
                 existUser·p0.999:  13.263 ms/op
                 existUser·p0.9999: 22.539 ms/op
                 existUser·p1.00:   23.167 ms/op

Iteration   2: 4.006 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.935 ms/op
                 existUser·p0.50:   3.789 ms/op
                 existUser·p0.90:   4.743 ms/op
                 existUser·p0.95:   5.505 ms/op
                 existUser·p0.99:   7.722 ms/op
                 existUser·p0.999:  15.544 ms/op
                 existUser·p0.9999: 20.448 ms/op
                 existUser·p1.00:   21.070 ms/op

Iteration   3: 4.044 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.593 ms/op
                 existUser·p0.50:   3.826 ms/op
                 existUser·p0.90:   4.956 ms/op
                 existUser·p0.95:   5.595 ms/op
                 existUser·p0.99:   7.078 ms/op
                 existUser·p0.999:  20.054 ms/op
                 existUser·p0.9999: 50.135 ms/op
                 existUser·p1.00:   50.659 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 234843
  mean =      4.088 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 213278 
    [ 5.000, 10.000) = 20985 
    [10.000, 15.000) = 328 
    [15.000, 20.000) = 113 
    [20.000, 25.000) = 107 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 21 
    [50.000, 55.000) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.593 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.932 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      7.479 ms/op
     p(99.9000) =     16.881 ms/op
     p(99.9900) =     47.683 ms/op
     p(99.9990) =     50.505 ms/op
     p(99.9999) =     50.659 ms/op
    p(100.0000) =     50.659 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 12.835 ±(99.9%) 0.188 ms/op
# Warmup Iteration   2: 4.853 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.413 ±(99.9%) 0.015 ms/op
Iteration   1: 4.318 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.612 ms/op
                 getUser·p0.50:   4.149 ms/op
                 getUser·p0.90:   5.145 ms/op
                 getUser·p0.95:   5.816 ms/op
                 getUser·p0.99:   7.684 ms/op
                 getUser·p0.999:  13.091 ms/op
                 getUser·p0.9999: 22.577 ms/op
                 getUser·p1.00:   22.938 ms/op

Iteration   2: 4.375 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.964 ms/op
                 getUser·p0.50:   4.174 ms/op
                 getUser·p0.90:   5.186 ms/op
                 getUser·p0.95:   6.038 ms/op
                 getUser·p0.99:   8.503 ms/op
                 getUser·p0.999:  22.571 ms/op
                 getUser·p0.9999: 28.432 ms/op
                 getUser·p1.00:   29.458 ms/op

Iteration   3: 4.282 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.460 ms/op
                 getUser·p0.50:   4.063 ms/op
                 getUser·p0.90:   5.226 ms/op
                 getUser·p0.95:   5.825 ms/op
                 getUser·p0.99:   7.422 ms/op
                 getUser·p0.999:  13.079 ms/op
                 getUser·p0.9999: 29.657 ms/op
                 getUser·p1.00:   30.966 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 221945
  mean =      4.325 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48 
    [ 2.500,  5.000) = 193652 
    [ 5.000,  7.500) = 25340 
    [ 7.500, 10.000) = 2204 
    [10.000, 12.500) = 404 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.460 ms/op
     p(50.0000) =      4.125 ms/op
     p(90.0000) =      5.186 ms/op
     p(95.0000) =      5.874 ms/op
     p(99.0000) =      7.897 ms/op
     p(99.9000) =     19.766 ms/op
     p(99.9900) =     28.967 ms/op
     p(99.9990) =     30.533 ms/op
     p(99.9999) =     30.966 ms/op
    p(100.0000) =     30.966 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 13.204 ±(99.9%) 0.202 ms/op
# Warmup Iteration   2: 5.336 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.080 ±(99.9%) 0.018 ms/op
Iteration   1: 4.911 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.911 ms/op
                 listUser·p0.50:   4.686 ms/op
                 listUser·p0.90:   5.751 ms/op
                 listUser·p0.95:   6.455 ms/op
                 listUser·p0.99:   9.011 ms/op
                 listUser·p0.999:  23.490 ms/op
                 listUser·p0.9999: 28.196 ms/op
                 listUser·p1.00:   29.131 ms/op

Iteration   2: 5.185 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.159 ms/op
                 listUser·p0.50:   4.956 ms/op
                 listUser·p0.90:   6.136 ms/op
                 listUser·p0.95:   6.849 ms/op
                 listUser·p0.99:   9.667 ms/op
                 listUser·p0.999:  20.283 ms/op
                 listUser·p0.9999: 26.313 ms/op
                 listUser·p1.00:   26.411 ms/op

Iteration   3: 4.986 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.572 ms/op
                 listUser·p0.50:   4.719 ms/op
                 listUser·p0.90:   5.784 ms/op
                 listUser·p0.95:   6.947 ms/op
                 listUser·p0.99:   10.453 ms/op
                 listUser·p0.999:  19.322 ms/op
                 listUser·p0.9999: 23.533 ms/op
                 listUser·p1.00:   23.790 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 190973
  mean =      5.024 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 121873 
    [ 5.000,  7.500) = 62866 
    [ 7.500, 10.000) = 4646 
    [10.000, 12.500) = 851 
    [12.500, 15.000) = 248 
    [15.000, 17.500) = 164 
    [17.500, 20.000) = 114 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      1.911 ms/op
     p(50.0000) =      4.776 ms/op
     p(90.0000) =      5.923 ms/op
     p(95.0000) =      6.726 ms/op
     p(99.0000) =      9.552 ms/op
     p(99.9000) =     20.120 ms/op
     p(99.9900) =     27.578 ms/op
     p(99.9990) =     28.833 ms/op
     p(99.9999) =     29.131 ms/op
    p(100.0000) =     29.131 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.314 ± 4.794  ops/ms
ClientPb.existUser                       thrpt       3   7.927 ± 4.456  ops/ms
ClientPb.getUser                         thrpt       3   7.367 ± 2.422  ops/ms
ClientPb.listUser                        thrpt       3   6.349 ± 2.086  ops/ms
ClientPb.createUser                       avgt       3   4.349 ± 1.222   ms/op
ClientPb.existUser                        avgt       3   4.185 ± 1.811   ms/op
ClientPb.getUser                          avgt       3   4.330 ± 0.958   ms/op
ClientPb.listUser                         avgt       3   5.103 ± 1.247   ms/op
ClientPb.createUser                     sample  217451   4.410 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.943           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.211           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.325           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.874           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.733           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.288           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.229           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.490           ms/op
ClientPb.existUser                      sample  234843   4.088 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.593           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.879           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.932           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.562           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.479           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.881           ms/op
ClientPb.existUser:existUser·p0.9999    sample          47.683           ms/op
ClientPb.existUser:existUser·p1.00      sample          50.659           ms/op
ClientPb.getUser                        sample  221945   4.325 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.460           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.125           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.186           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.874           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.897           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.766           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.967           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.966           ms/op
ClientPb.listUser                       sample  190973   5.024 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.911           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.776           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.923           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.726           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.552           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.120           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.578           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.131           ms/op
