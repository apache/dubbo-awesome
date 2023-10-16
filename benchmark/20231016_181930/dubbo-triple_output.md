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
# Warmup Iteration   1: 1.943 ops/ms
# Warmup Iteration   2: 4.540 ops/ms
# Warmup Iteration   3: 7.646 ops/ms
Iteration   1: 8.029 ops/ms
Iteration   2: 8.478 ops/ms
Iteration   3: 8.306 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.271 ±(99.9%) 4.137 ops/ms [Average]
  (min, avg, max) = (8.029, 8.271, 8.478), stdev = 0.227
  CI (99.9%): [4.134, 12.408] (assumes normal distribution)


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
# Warmup Iteration   1: 2.501 ops/ms
# Warmup Iteration   2: 7.631 ops/ms
# Warmup Iteration   3: 8.372 ops/ms
Iteration   1: 8.448 ops/ms
Iteration   2: 8.550 ops/ms
Iteration   3: 8.389 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.462 ±(99.9%) 1.486 ops/ms [Average]
  (min, avg, max) = (8.389, 8.462, 8.550), stdev = 0.081
  CI (99.9%): [6.976, 9.948] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.512 ops/ms
# Warmup Iteration   2: 7.634 ops/ms
# Warmup Iteration   3: 7.937 ops/ms
Iteration   1: 8.347 ops/ms
Iteration   2: 8.034 ops/ms
Iteration   3: 8.433 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.271 ±(99.9%) 3.838 ops/ms [Average]
  (min, avg, max) = (8.034, 8.271, 8.433), stdev = 0.210
  CI (99.9%): [4.434, 12.109] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.078 ops/ms
# Warmup Iteration   2: 5.955 ops/ms
# Warmup Iteration   3: 6.729 ops/ms
Iteration   1: 6.785 ops/ms
Iteration   2: 7.093 ops/ms
Iteration   3: 6.883 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.920 ±(99.9%) 2.869 ops/ms [Average]
  (min, avg, max) = (6.785, 6.920, 7.093), stdev = 0.157
  CI (99.9%): [4.052, 9.789] (assumes normal distribution)


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
# Warmup Iteration   1: 10.268 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.334 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.073 ±(99.9%) 0.005 ms/op
Iteration   1: 4.068 ±(99.9%) 0.005 ms/op
Iteration   2: 3.965 ±(99.9%) 0.006 ms/op
Iteration   3: 3.818 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.950 ±(99.9%) 2.289 ms/op [Average]
  (min, avg, max) = (3.818, 3.950, 4.068), stdev = 0.125
  CI (99.9%): [1.661, 6.239] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 10.505 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.259 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.895 ±(99.9%) 0.003 ms/op
Iteration   1: 3.686 ±(99.9%) 0.006 ms/op
Iteration   2: 3.849 ±(99.9%) 0.004 ms/op
Iteration   3: 3.813 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.782 ±(99.9%) 1.561 ms/op [Average]
  (min, avg, max) = (3.686, 3.782, 3.849), stdev = 0.086
  CI (99.9%): [2.221, 5.344] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.982 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.585 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.927 ±(99.9%) 0.005 ms/op
Iteration   1: 3.752 ±(99.9%) 0.006 ms/op
Iteration   2: 3.867 ±(99.9%) 0.005 ms/op
Iteration   3: 3.826 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.815 ±(99.9%) 1.068 ms/op [Average]
  (min, avg, max) = (3.752, 3.815, 3.867), stdev = 0.059
  CI (99.9%): [2.747, 4.882] (assumes normal distribution)


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
# Warmup Iteration   1: 14.731 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 5.403 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.739 ±(99.9%) 0.006 ms/op
Iteration   1: 4.744 ±(99.9%) 0.004 ms/op
Iteration   2: 4.664 ±(99.9%) 0.006 ms/op
Iteration   3: 4.604 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.671 ±(99.9%) 1.281 ms/op [Average]
  (min, avg, max) = (4.604, 4.671, 4.744), stdev = 0.070
  CI (99.9%): [3.389, 5.952] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 12.063 ±(99.9%) 0.174 ms/op
# Warmup Iteration   2: 4.467 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.173 ±(99.9%) 0.016 ms/op
Iteration   1: 3.920 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.276 ms/op
                 createUser·p0.50:   3.680 ms/op
                 createUser·p0.90:   4.563 ms/op
                 createUser·p0.95:   5.677 ms/op
                 createUser·p0.99:   8.345 ms/op
                 createUser·p0.999:  19.702 ms/op
                 createUser·p0.9999: 21.922 ms/op
                 createUser·p1.00:   24.838 ms/op

Iteration   2: 3.975 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.704 ms/op
                 createUser·p0.50:   3.863 ms/op
                 createUser·p0.90:   4.604 ms/op
                 createUser·p0.95:   4.923 ms/op
                 createUser·p0.99:   7.627 ms/op
                 createUser·p0.999:  18.512 ms/op
                 createUser·p0.9999: 21.037 ms/op
                 createUser·p1.00:   21.922 ms/op

Iteration   3: 3.998 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.161 ms/op
                 createUser·p0.50:   3.789 ms/op
                 createUser·p0.90:   4.702 ms/op
                 createUser·p0.95:   5.022 ms/op
                 createUser·p0.99:   7.578 ms/op
                 createUser·p0.999:  24.805 ms/op
                 createUser·p0.9999: 28.312 ms/op
                 createUser·p1.00:   35.258 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 242177
  mean =      3.964 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1001 
    [ 2.500,  5.000) = 228319 
    [ 5.000,  7.500) = 9581 
    [ 7.500, 10.000) = 2250 
    [10.000, 12.500) = 456 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 118 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      5.054 ms/op
     p(99.0000) =      7.979 ms/op
     p(99.9000) =     20.546 ms/op
     p(99.9900) =     27.571 ms/op
     p(99.9990) =     31.934 ms/op
     p(99.9999) =     35.258 ms/op
    p(100.0000) =     35.258 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 11.103 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 4.046 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.901 ±(99.9%) 0.013 ms/op
Iteration   1: 3.766 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.757 ms/op
                 existUser·p0.50:   3.633 ms/op
                 existUser·p0.90:   4.268 ms/op
                 existUser·p0.95:   4.841 ms/op
                 existUser·p0.99:   7.975 ms/op
                 existUser·p0.999:  15.813 ms/op
                 existUser·p0.9999: 22.577 ms/op
                 existUser·p1.00:   27.066 ms/op

Iteration   2: 3.854 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.141 ms/op
                 existUser·p0.50:   3.731 ms/op
                 existUser·p0.90:   4.334 ms/op
                 existUser·p0.95:   4.760 ms/op
                 existUser·p0.99:   7.135 ms/op
                 existUser·p0.999:  21.857 ms/op
                 existUser·p0.9999: 27.791 ms/op
                 existUser·p1.00:   29.098 ms/op

Iteration   3: 3.805 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.090 ms/op
                 existUser·p0.50:   3.609 ms/op
                 existUser·p0.90:   4.366 ms/op
                 existUser·p0.95:   5.022 ms/op
                 existUser·p0.99:   8.282 ms/op
                 existUser·p0.999:  15.761 ms/op
                 existUser·p0.9999: 27.460 ms/op
                 existUser·p1.00:   29.393 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 252051
  mean =      3.808 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2045 
    [ 2.500,  5.000) = 238994 
    [ 5.000,  7.500) = 7843 
    [ 7.500, 10.000) = 2070 
    [10.000, 12.500) = 642 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 70 

  Percentiles, ms/op:
      p(0.0000) =      1.090 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      7.881 ms/op
     p(99.9000) =     18.738 ms/op
     p(99.9900) =     27.295 ms/op
     p(99.9990) =     29.098 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 11.661 ±(99.9%) 0.161 ms/op
# Warmup Iteration   2: 4.420 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.883 ±(99.9%) 0.011 ms/op
Iteration   1: 4.086 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.700 ms/op
                 getUser·p0.50:   3.805 ms/op
                 getUser·p0.90:   4.637 ms/op
                 getUser·p0.95:   6.447 ms/op
                 getUser·p0.99:   9.470 ms/op
                 getUser·p0.999:  21.201 ms/op
                 getUser·p0.9999: 23.790 ms/op
                 getUser·p1.00:   24.773 ms/op

Iteration   2: 4.013 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.884 ms/op
                 getUser·p0.50:   3.793 ms/op
                 getUser·p0.90:   4.645 ms/op
                 getUser·p0.95:   5.292 ms/op
                 getUser·p0.99:   7.864 ms/op
                 getUser·p0.999:  22.576 ms/op
                 getUser·p0.9999: 28.448 ms/op
                 getUser·p1.00:   30.245 ms/op

Iteration   3: 3.963 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.759 ms/op
                 getUser·p0.50:   3.764 ms/op
                 getUser·p0.90:   4.483 ms/op
                 getUser·p0.95:   5.284 ms/op
                 getUser·p0.99:   7.807 ms/op
                 getUser·p0.999:  25.176 ms/op
                 getUser·p0.9999: 34.472 ms/op
                 getUser·p1.00:   35.127 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 238629
  mean =      4.020 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 323 
    [ 2.500,  5.000) = 222094 
    [ 5.000,  7.500) = 10988 
    [ 7.500, 10.000) = 4223 
    [10.000, 12.500) = 446 
    [12.500, 15.000) = 131 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.700 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      8.151 ms/op
     p(99.9000) =     21.803 ms/op
     p(99.9900) =     33.620 ms/op
     p(99.9990) =     34.935 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


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
# Warmup Iteration   1: 12.545 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 5.142 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.639 ±(99.9%) 0.017 ms/op
Iteration   1: 4.684 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.994 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   8.667 ms/op
                 listUser·p0.999:  23.953 ms/op
                 listUser·p0.9999: 28.001 ms/op
                 listUser·p1.00:   28.312 ms/op

Iteration   2: 4.669 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.987 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   9.077 ms/op
                 listUser·p0.999:  17.203 ms/op
                 listUser·p0.9999: 19.923 ms/op
                 listUser·p1.00:   24.084 ms/op

Iteration   3: 4.654 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.564 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.349 ms/op
                 listUser·p0.99:   8.749 ms/op
                 listUser·p0.999:  17.727 ms/op
                 listUser·p0.9999: 23.237 ms/op
                 listUser·p1.00:   27.132 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 205495
  mean =      4.669 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40 
    [ 2.500,  5.000) = 175675 
    [ 5.000,  7.500) = 25056 
    [ 7.500, 10.000) = 3693 
    [10.000, 12.500) = 352 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 283 
    [17.500, 20.000) = 118 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 45 

  Percentiles, ms/op:
      p(0.0000) =      0.994 ms/op
     p(50.0000) =      4.530 ms/op
     p(90.0000) =      5.136 ms/op
     p(95.0000) =      5.513 ms/op
     p(99.0000) =      8.831 ms/op
     p(99.9000) =     18.383 ms/op
     p(99.9900) =     26.673 ms/op
     p(99.9990) =     28.310 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.271 ± 4.137  ops/ms
ClientPb.existUser                       thrpt       3   8.462 ± 1.486  ops/ms
ClientPb.getUser                         thrpt       3   8.271 ± 3.838  ops/ms
ClientPb.listUser                        thrpt       3   6.920 ± 2.869  ops/ms
ClientPb.createUser                       avgt       3   3.950 ± 2.289   ms/op
ClientPb.existUser                        avgt       3   3.782 ± 1.561   ms/op
ClientPb.getUser                          avgt       3   3.815 ± 1.068   ms/op
ClientPb.listUser                         avgt       3   4.671 ± 1.281   ms/op
ClientPb.createUser                     sample  242177   3.964 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.161           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.781           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.628           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.054           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.979           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.546           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.571           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.258           ms/op
ClientPb.existUser                      sample  252051   3.808 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.090           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.654           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.325           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.858           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.881           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.738           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.295           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.393           ms/op
ClientPb.getUser                        sample  238629   4.020 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.700           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.789           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.588           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.816           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.151           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.803           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.620           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.127           ms/op
ClientPb.listUser                       sample  205495   4.669 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.994           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.136           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.513           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.831           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.383           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.673           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.312           ms/op
